## Why GitHub?

### What are the benefits?
- Learning
- Sharing
- Collaboration

### What people use it for?
- Writing Books:
  - [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- Sharing Presentations/Workshops:
  - [https://github.com/kentcdodds/testing-workshop](https://github.com/kentcdodds/testing-workshop)
  - [https://github.com/derberg/rest-api-docu-best-practices](https://github.com/derberg/rest-api-docu-best-practices)
- Blogging/Publishing
  - [https://github.com/derberg/awesome-docs-with-static-site-generators](https://github.com/derberg/awesome-docs-with-static-site-generators)
- Sharing thoughts:
  - [https://gist.github.com/matthewmccullough/9381765](https://gist.github.com/matthewmccullough/9381765)
  - [https://gist.github.com/olivierlacan/4062929](https://gist.github.com/olivierlacan/4062929)
  - [https://gist.github.com/rxaviers/7360908](https://gist.github.com/rxaviers/7360908)
  
### Who uses it?
  - [https://github.com/Microsoft](https://github.com/Microsoft)
  - [https://github.com/google](https://github.com/google)
  - [https://github.com/sap](https://github.com/sap)
  - [https://github.com/facebook](https://github.com/facebook)
  
  The answer is: Everybody, like with Facebook. Except for those geeks that go to GitLab, like Facebook haters go to Google Plus.

### What GitHub changed in the IT world
  [https://honza.ca/2011/03/7-ways-github-has-changed-the-open-source-world](https://honza.ca/2011/03/7-ways-github-has-changed-the-open-source-world)
  
  This post was published exactly when GitHub populatiry started rising. It is still valid. 
  GitHub changed not only developers, but also technical writers lives:
  - Static site generators
  - Markdown popularity
  - Readme driven development
  - Overall awareness of how important it is to have high-quality documentation

## Glossary

- GitHub: Instagram for developers
- Repository: An instagram profile with fancy stuff (you can have many profiles sic! :D)
- Clone: Copy sb's repo (profile) to work on it locally
- Fork: Kind of clone with the assumption to contribute to an existing repo or to extend it separately (you can add your pictures to somebody's profile) 
- Pull Request: A request sent to the profile owner to make the pictures you added to their profile visible to all
- Branches: Different versions of a profile with extra photos, changes, work in progress
- Commit: Save changes
- Local vs. Remote: On your machine / on a server
- Push/Pull: Send the changes you made on your local version to the server / download sb else's changes from the server to your local version
- Merge: Combine different branches in one
- Merge Conflict: RUN FOR YOUR LIFE!

## GitHub online editing vs. local editing

This workshop is fully based on GitHub functionality to show that Git clients usage is needed only in case of advanced users.

Git is a distributed version control system. In human words: A system that records changes to a file or a set of files over time so that you can recall specific versions later.

No GitHub? Do you use Bitbucket?
- [Git CLI](https://git-scm.com/downloads). Easy to start with thanks to [this free training](https://try.github.io)
- [GitHub Desktop](https://desktop.github.com/)
- [SourceTree](https://www.sourcetreeapp.com/)

Stick to the tool that your team mates use.

## Contribution flows

Basic workflow:
1. Create a repository
2. Create a 'feature' branch from the 'master' 
3. Make and commit your changes
4. Open a pull request
5. Merge the pull request into the 'master'


- Project member:
  - Edit -> Commit
  - **Clone repo** -> **Create branch** -> Edit -> Commit -> **Open pull request**
- Project non-member: **Fork** repo -> Create branch -> Edit -> Commit -> Open pull request

## Crowdsourcing

[https://kubernetes.io/docs/tutorials/object-management-kubectl/imperative-object-management-configuration/](https://kubernetes.io/docs/tutorials/object-management-kubectl/imperative-object-management-configuration/)

The edit view looks like [this](https://github.com/Writers-Instagram/play-bucket/edit/master/README.md).

Sample contribution that proved that it works: [https://github.com/kubernetes-incubator/service-catalog/pull/1878](https://github.com/kubernetes-incubator/service-catalog/pull/1878).

## Markdown and others

Markdown is a human-readable markup language used to style text on the web

- Basics: [https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)
- Editors: [https://dillinger.io/](https://dillinger.io/)
- Tutorial: [http://commonmark.org/help/tutorial/](http://commonmark.org/help/tutorial/)

Emoticons: [https://gist.github.com/rxaviers/7360908](https://gist.github.com/rxaviers/7360908)

Other markup languages: [https://github.com/github/markup#markups](https://github.com/github/markup#markups)

## Ways of documenting projects

- Simple docu, readme only: [https://github.com/matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)
- Readme with links to more docs: [https://github.com/matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)
- Wiki: [https://github.com/Netflix/Hystrix/wiki](https://github.com/Netflix/Hystrix/wiki)
- Jekyll site: [https://github.com/derberg/awesome-docs-with-static-site-generators](https://github.com/derberg/awesome-docs-with-static-site-generators)

## GitHub Pages

Free web hosting: [https://pages.github.com/](https://pages.github.com/)

- Easy -> Plain README: [https://pages.github.com/themes/](https://pages.github.com/themes/)
- Advanced -> Custom: [https://github.com/derberg/awesome-docs-with-static-site-generators](https://github.com/derberg/awesome-docs-with-static-site-generators)

Alternative: 
* `http://documentup.com/profile-org-name/repo-name` like [http://documentup.com/Writers-Instagram/GitHub-for-technical-writers-WORKSHOP](http://documentup.com/Writers-Instagram/GitHub-for-technical-writers-WORKSHOP)
* [https://github.com/PharkMillups/beautiful-docs](https://github.com/PharkMillups/beautiful-docs)
