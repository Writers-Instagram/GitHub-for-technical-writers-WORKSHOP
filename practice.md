## Contribution with pull requests

1. Go to the [play-bucket](https://github.com/Writers-Instagram/play-bucket) repository.
2. Create a new file or edit an existing file through the Fork workflow. Propose your changes and open a pull request, so it can be accepted and merged.

Advanced: now let us simulate a merge conflict :wink:

## Create your own repository with a README.md with external links

1. Create a new repository on your GitHub profile: https://github.com/{your-profile-name}?tab=repositories.
2. Create a few Markdown files, including README.md. You can use [https://jaspervdj.be/lorem-markdownum](https://jaspervdj.be/lorem-markdownum/) to generate content.
3. Link your files one to another. Broken links are very welcome as they will be used in the next exercise of the script.

## GitHub Pages

1. Go to the **Settings** tab of your repository. 
2. In the **GitHub Pages** section select a source to enable GitHub Pages.
3. Choose the theme you like the most.

Take a look at [this example](https://writers-instagram.github.io/GitHub-for-technical-writers-WORKSHOP/) of a GitHub Page enabled for this script. 

## Automation for links validation

Continuous integration is a way of automating processes around your project.
- [https://travis-ci.org](https://travis-ci.org)
- [https://circleci.com](https://circleci.com)

### TravisCI

1. Enable Travis to gain access to your repository: https://travis-ci.org/profile/.
2. Create such a [.travis.yml](.travis.yml) file in the root of your repository. To get more understanding of the tool used here for links validation, read its docs: [https://github.com/dkhamsing/awesome_bot](https://github.com/dkhamsing/awesome_bot).
3. Check how your CI plan is doing: https://travis-ci.org/profile-org-name/repo-name.
4. Add the following badge at the top of your README:
   ```
   [![Build Status](https://travis-ci.org/profile-org-name/repo-name.svg?branch=master)](https://travis-ci.org/profile-org-name/repo-name)
   ```

### CircleCI

1. Enable CircleCI to gain access to your repository: https://circleci.com/signup/.
1. Create such a [config.yml](.circleci/config.yml) file in a new **.circleci** directory.
1. Check how your CI plan is doing: https://circleci.com/gh/profile-org-name/repo-name.
1. Add the following badge at the top of your README:
   ```
   [![CircleCI](https://circleci.com/gh/profile-org-name/repo-name/tree/master.svg?style=svg)](https://circleci.com/gh/profile-org-name/repo-name/tree/master)
   ```

