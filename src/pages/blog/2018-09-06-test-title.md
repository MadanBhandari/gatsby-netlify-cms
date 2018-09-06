---
templateKey: blog-post
title: New Title
date: '2018-09-06T17:23:36+05:30'
description: >-
  This is just a simple test post. This is just a simple test post. This is just
  a simple test post. This is just a simple test post. 
tags:
  - test title
---
Continuous Deployment



Continuous deployment works by connecting a git repository to a Netlify site and keeping the two in sync.



It works for plain static sites, but it’s even more powerful when you’re using a static site generator or a frontend build tool like Grunt, Gulp or Broccoli.



Netlify will run your build command and deploy the result whenever you push to your Git repo.



No deploying without committing and pushing first

Easy collaboration through pull requests

Fix a typo through your Git provider’s web UI from your mobile

Edit content without code by using a static site CMS, Netlify CMS

Branches & Deploys

DEFINITIONS

Production branch: the Git branch that Netlify uses to build and deploy changes to your site’s main URL, for example www.yourcustomdomain.com and yoursitename.netlify.com.

Production deploy: a deploy from the production branch. If auto publishing is enabled, each new production deploy will update what is published at your site’s main URL.

Branch deploy: a deploy generated from a branch that is not your Production branch. Branch deploys are published to a URL which includes the branch name as a prefix. For example, if a branch is called staging, it will deploy to staging--yoursitename.netlify.com. If you use Netlify DNS, you can enable branch subdomains, so the staging branch example would deploy to staging.yourcustomdomain.com.

Deploy Preview: Deploy generated from a pull request or merge request, building the site as it would be if the proposed changes were merged. Deploy Previews are published to a URL which has the prefix deploy-preview followed by the identifier number of the pull request or merge request. For example, pull request #42 will automatically trigger a Deploy Preview at deploy-preview-42--yoursitename.netlify.com.

BRANCH DEPLOY CONTROLS

Netlify lets you control which branches in your Git repository you want to deploy. By default, Netlify deploys the site’s production branch after every change, and builds deploy previews for all pull/merge requests on that branch.



To generate branch deploys for other branches in your repository, go to Settings > Build & deploy > Continuous Deployment > Deploy settings, then click Edit settings. You can choose to deploy all branches (including future branches), or select individual branches you would like to deploy.
