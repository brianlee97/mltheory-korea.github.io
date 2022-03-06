# mltheory-korea.github.io

Homepage for ML Theory @ Korea

## Local development guide

It is generally not recommended to commit directly to the 'main' branch.

1. Create a new branch with `git checkout -b [new_branch_name]`.

1. Commit your patches to the new branch.

1. Push to GitHub by `git push -u origin [new_branch_name]`.

1. Open our GitHub repository and you will find a message that suggests to create a Pull Request (PR).

1. Create a PR. If needed, you may request other members to review your PR.

It is fine to self merge your PR if you are sure. This is not a serious software development! However, it is often convenient to keep track of the changes we have made. This is why it is recommended to create a PR even if you made a very small patch.

### Running locally

To test your changes, you should be able to run the homepage locally. Here is a brief guide about this.

Reference: [academicpages](https://github.com/academicpages/academicpages.github.io#to-run-locally-not-on-github-pages-to-serve-on-your-own-computer)

1. Install [rbenv](https://github.com/rbenv/rbenv) and [bundler](https://bundler.io/)

1. Run `rbenv local 2.5.3`

1. Run `bundle exec jekyll liveserve --config _config.dev.yml`

1. Open the local webpage at http://localhost:4000.

### Configuration file

You do not have to modify `config.yml` or `config.dev.yml` unless you know what you are doing. If you do have to, however, make sure you apply your changes to the both configuration files.

### Others

A more detailed guide on writing a blog post, schedule a new seminar, etc. will arrive after the homepage becomes more organized.
