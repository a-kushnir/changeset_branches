<img src="https://user-images.githubusercontent.com/1454297/93050547-4da0ed80-f620-11ea-9ccc-1b6afa39d006.png" alt="Redmine logo" title="Redmine" align="right" height="60" />

# Changeset Branches

[![Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos%20%7C%20linux-blue)](https://img.shields.io/badge/platform-windows%20%7C%20macos%20%7C%20linux-blue)
[![Language](https://img.shields.io/badge/language-ruby-orange)](https://img.shields.io/badge/language-ruby-orange)
[![Redmine](https://img.shields.io/badge/plugin-redmine-orange)](https://img.shields.io/badge/plugin-redmine-orange)
[![License](https://img.shields.io/github/license/a-kushnir/x-stocks)](https://img.shields.io/github/license/a-kushnir/changeset-branches)

A Redmine plugin that adds branches for Associated revisions section on Issue page.

# Table of contents

- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)
- [Links](#links)

# Requirements

[(Back to top)](#table-of-contents)

* Linux or macOS or Windows
* Ruby, [download](https://www.ruby-lang.org/en/downloads/)
* RedMine, [download](https://github.com/redmine/redmine)
* Git

# Installation

[(Back to top)](#table-of-contents)

1. Clone this repository
```
$ git clone https://github.com/a-kushnir/changeset_branches.git
```
2. Put them in _redmine/plugins_ directory
3. Run migrations
```
$ rails db:migrate
```
4. Restart Redmine

# License

[(Back to top)](#table-of-contents)

Changeset Branches plugin is under the MIT license. See the [LICENSE](https://github.com/a-kushnir/changeset_branches/blob/master/LICENSE) for more information.

# Links

[(Back to top)](#table-of-contents)

* [Source code](https://github.com/a-kushnir/changeset_branches)
* [Redmine view override](http://www.redmine.org/boards/3/topics/33949)
* [Git branches for commit](https://github.com/mikoto20000/redmine_git_branch_hook)
