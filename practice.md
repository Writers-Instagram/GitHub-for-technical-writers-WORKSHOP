## Contribution with pull requests

1. Go to [play-bucket](https://github.com/Writers-Instagram/play-bucket) repository
1. Suggest new file creation or change in some existing file through the Fork workflow. Make a change and propose a pull request, so it can be accepted and merged.

Advanced: now let us simulate a merge conflict :wink:

## Create own repository with README with external links

1. Create new repository in your GitHub profile: https://github.com/{your-profile-name}?tab=repositories
1. Create few markdown files, including README.md. You can use https://jaspervdj.be/lorem-markdownum/ to generate the content.
1. Link those docs one to another. Broken links are very welcome because of next sections of the script.

## GitHub Pages

1. Go to settings tab of your repository. In **GitHub Pages** section enable them and choose the theme you like the most

Take a look on example GitHub Page enabled for this script: https://writers-instagram.github.io/GitHub-for-technical-writers-WORKSHOP/

## Automation for links validation

Continuous integration is a way of automating processes aroung your project.
- https://travis-ci.org
- https://circleci.com/

### TravisCI

1. Enable Travis to gain access to your repository: https://travis-ci.org/profile/
2. Create such [.travis.yml](.travis.yml) file in the root of your repository. To get more understanding around the tool used here for links validation, read its docs: https://github.com/dkhamsing/awesome_bot
3. Check how is your CI plan doing: https://travis-ci.org/profile-org-name/repo-name
4. Add a badge to the top of the README:
   ```
   [![Build Status](https://travis-ci.org/profile-org-name/repo-name.svg?branch=master)](https://travis-ci.org/profile-org-name/repo-name)
   ```

### CircleCI

1. Enable CircleCI to gain access to your repository: https://circleci.com/signup/
1. Create such [config.yml](.circleci/config.yml) file in new **.circleci** directory.
1. Check how is your CI plan doing: https://circleci.com/gh/profile-org-name/repo-name
1. Add a badge to the top of the README:
   ```
   [![CircleCI](https://circleci.com/gh/profile-org-name/repo-name/tree/master.svg?style=svg)](https://circleci.com/gh/profile-org-name/repo-name/tree/master)
   ```

