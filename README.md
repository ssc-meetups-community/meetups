# README

Contributors' guide:

## Making small changes (updating meetup changes)

1. If you are member of our github org, you should be able to use GitHub UI to edit the text files (`index.md, oldmeetups.md`). This should be easy enough.
2. ([Assuming you know what you are doing.](https://git-scm.com/docs/gittutorial)) Fork the repository, edit the `*.md` files in your favorite text editor, commit changes to git, and PR / push.

## Major contributions

Like changing the website format etc: Please make a pull request.

## Anything else or not sure about something

Please create an issue.

## Running locally

If you want to build the site locally to test your changes, you need:

- Git
- [Ruby 2.1.x or higher](https://www.ruby-lang.org/en/downloads/)
- bundler (`gem install bundler`)
- run `bundle install`
- run `bundle exec jekyll serve`. you should be able to view local website at `http://localhost:4000`
