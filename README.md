# OpenMRS REST API documentation

OpenMRS documentation is built using [Slate](https://github.com/tripit/slate).

# Getting Started with Slate
### Prerequisites

You're going to need:

 - **Linux or macOS** — Windows may work, but is unsupported.
 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Fork this repository on GitHub.
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/YOURUSERNAME/OpenMRS-docs.git`
3. `cd OpenMRS-docs`
4. Initialize and start OpenMRS-docs. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

## Editing documentation content


All documentation is in `includes` directory, and uses Markdown text format,
plus some Slate widgets (such as notices).

