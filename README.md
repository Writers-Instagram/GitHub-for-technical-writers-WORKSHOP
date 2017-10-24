[![Build Status](https://travis-ci.org/Writers-Instagram/GitHub-for-technical-writers-WORKSHOP.svg?branch=master)](https://travis-ci.org/Writers-Instagram/GitHub-for-technical-writers-WORKSHOP)

Purpose of this workshop is to:
* Get started with GitHub and get convinced to use it on daily basis
* Learn basics about Git and GitHub
* Know what are the benefits of using Github
* What to use GitHub for
* Get more experience and find a geeky job https://github.com/trending?since=monthly

So first, get your own GitHub account https://github.com/join?source=header-home

## Sample Data

All sample data in this project are technology agnostic and are based on dummy lorem ipsum content taken from https://jaspervdj.be/lorem-markdownum/

## Why GitHub?

### Who uses it?
  - https://github.com/Microsoft
  - https://github.com/google
  - https://github.com/sap
  - https://github.com/facebook
  
  Answer is: Everybody, like with Facebook. Except of those geeks that go to GitLab, like Facebook haters go to Google Plus.
### What GitHub changed in the IT world
  https://honza.ca/2011/03/7-ways-github-has-changed-the-open-source-world
  This post was published exactly when the GitHub populatiry started rising. It is still valid. 
  GitHub didn't change only developers lives, but also technical writers lives:
  - Static site generators
  - Markdown popularity
  - Readme driven development
  - Overall awareness of how important it is to have a good documentation quality
### What are the benefits?
- Learning
- Sharing
- Collaboration
### What people use it for?
- Writing Books:
  - https://github.com/getify/You-Dont-Know-JS
- Sharing Presentations/workshops:
  - https://github.com/kentcdodds/testing-workshop
  - https://github.com/derberg/rest-api-docu-best-practices
- Blogging/Publishing
  - https://github.com/derberg/awesome-docs-with-static-site-generators
- Sharing thoughts:
  - https://gist.github.com/matthewmccullough/9381765
  - https://gist.github.com/olivierlacan/4062929

## Glossary

- GitHub: Instagram for developers
- Repository: like an instagram profile with fancy stuff (you can have many profiles sic! :D)
- Clone: Copy sb's repo (profile) to work on it locally
- Fork: Kind of cloning with the assumption to contribute to an existing repo (you can add your pictures to somebody's profile) or to extend it separately
- Pull Request: A request sent to the profile owner to make the pictures you added to their profile visible to all
- Branches: Different versions of the profile with extra photos, changes, work in progress
- Commit: Saving changes
- Push/Pull: Send or download the changes to local version
- Local vs Remote: On your machine / on a server
- Merge: Combine different branches in one
- Merge Conflict: RUN FOR YOUR LIFE!

## GitHub online editing vs local editing

This workshop is fully based on GitHub functionality, to show that Git clients usage is needed only in case of advance users.

Git is a distributet version control system. In human words: A system that records changes to a file or set of files over time so that you can recall specific versions later.

No GitHub? Are you using Bitbucket?
- [Git CLI](https://git-scm.com/downloads). Easy to start with thatnks to this free training https://try.github.io
- https://desktop.github.com/
- https://www.sourcetreeapp.com/
Stick to the tool that your team mates use.

## Contribution flows

All workshop patricipants must be members of https://github.com/Writers-Instagram/play-bucket repository.
Share accounts names with https://docs.google.com/document/u/0/.

- Project member:
  - Edit -> Commit
  - Clone -> Branch -> Pull Request
- Through forks: Fork -> Pull Request

## Crowd sourcing 

https://kubernetes.io/docs/tutorials/object-management-kubectl/imperative-object-management-configuration/

Edit link looks like this https://github.com/Writers-Instagram/play-bucket/edit/master/README.md

## Markdown and others

Markdown is a way to style text on the web

- Basics: https://daringfireball.net/projects/markdown/syntax, 
- Editors: https://dillinger.io/
- Tutorial https://www.markdowntutorial.com/

Emoticons: https://gist.github.com/rxaviers/7360908

Others: https://github.com/github/markup#markups AsciiDoc or reStructuredText.

## Ways of documenting projects

- Simple docu, readme only: https://github.com/matiassingers/awesome-readme
- Readme with links to more docs: https://github.com/matiassingers/awesome-readme
- Wiki: https://github.com/Netflix/Hystrix/wiki
- Jekyll site: https://github.com/derberg/awesome-docs-with-static-site-generators

## GitHub Pages

Free web hosting: https://pages.github.com/

- Easy -> Plain README: https://pages.github.com/themes/
- Advanced -> Custom: https://github.com/derberg/awesome-docs-with-static-site-generators

## [Optional] Gist?

Create first Gist https://gist.github.com

## [Optional] Automation, Travis, links validation

Continuous integration is a way of automating processes aroung your project.
- https://travis-ci.org
- https://circleci.com/

1. Enable Travis to gain access to your repository: https://travis-ci.org/profile/
2. Create such [.travis.yml](/blob/master/.travis.yml) file in the root of your repository
3. Check how is your CI plan doing: https://travis-ci.org/profile-org-name/repo-name
4. Add a badge to the top of the README:
```
[![Build Status](https://travis-ci.org/Writers-Instagram/GitHub-for-technical-writers-WORKSHOP.svg?branch=master)](https://travis-ci.org/Writers-Instagram/GitHub-for-technical-writers-WORKSHOP)
```

## [Optional] Project management through Project and Issues

Define a [project](/projects) and start working with [issues](/issues) to assure transparency of your project for the community. Define your own [issue template](https://github.com/YaaS/chewie/blob/master/ISSUE_TEMPLATE.md) to make issue reporting much easier and assure you're getting all important data immediately from the user
