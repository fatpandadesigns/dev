Change Log
==========

[0.4.2][] (2015-09-01)
----------------------

bug fixes for 0.4.1

Details:

- Bug
    + [DEV-209] - Fix ~/.bash_profile permission and on other locations

- Task
    + [DEV-244] - release teracy-dev v0.4.2


[0.4.1][] (2015-05-29)
----------------------

bug fixes for 0.4.0

Details:

- Bug
    + [DEV-232] - mysql with php not work
    + [DEV-233] - wrong default forwarded port for mysql

- Task
    + [DEV-234] - release teracy-dev v0.4.1, update blog post


[0.4.0][] (2015-05-15)
----------------------

The next milestone release includes:

- add .bat automatic installation script
- multiple python versions
- LAMP, LEMP stack support
- Ruby on Rails stack support
- Built-in IDE (codebox) support
- Improve Vagrant configuration
- Support optional sync methods along with default sharing folder method
- Documentation improvements
- Bug fixes and improvements


Details:

- Sub-task
    + [DEV-126] - Fix foodcritic violations when upgrade
    + [DEV-201] - update php dev guide
    + [DEV-214] - update databases guide
    + [DEV-216] - update nodejs dev guide
    + [DEV-217] - update python dev guide


- Bug
    + [DEV-93] - virtualenvwrapper not work
    + [DEV-101] - nosetests does not work well on vagrantbox
    + [DEV-109] - permission denied of .virtualenvs on windows
    + [DEV-121] - No "source" of install_method for mongodb recipe
    + [DEV-134] - don't reinstall php when $ vagrant reload --provision
    + [DEV-136] - fix Could not find mixlib-shellout-1.6.0 in any of the sources error on travis-ci
    + [DEV-151] - git installer did not work properly
    + [DEV-161] - problems related to virtualbox guest addition for v0.4.0
    + [DEV-162] - auto generated key pair by vagrant 1.7.1 did not work with `$ vagrant ssh`
    + [DEV-168] - fix apache2 cache bug
    + [DEV-171] - .htaccess not working
    + [DEV-193] - Failed to install `amo-validator` via pip globals config
    + [DEV-210] - Need to set default date.timezone = UTC for php.ini


- Improvement
    + [DEV-76] - Adding loading indicator bar to .bat installation script
    + [DEV-83] - Support python.version config
    + [DEV-97] - Improve Getting Started
    + [DEV-99] - Reduce the provision time of base box v0.3.0 on v0.3.0
    + [DEV-111] - improve java, maven cookbook
    + [DEV-118] - Support Linux, Apache, MySQL, PHP (LAMP) stack to deploy PHP applications
    + [DEV-120] - [DOC] Improve the section Ruby training
    + [DEV-143] - add support to use nginx instead of default apache server
    + [DEV-157] - Add all options for Vagrantfile config.vm settings
    + [DEV-169] - remove "git" from vagrant_config.json's chef_recipes
    + [DEV-176] - Don't force apt-get update by default on mysql recipe
    + [DEV-177] - Avoid using vagrant 1.7.2 for now, use 1.7.1 instead
    + [DEV-188] - Support for Ruby on Rails, Sinatra development
    + [DEV-189] - make sure to support provisioning from a clean ubuntu base box
    + [DEV-190] - Enable ruby by default
    + [DEV-195] - By default use fmode=755 instead of fmode=644 for workspace directory
    + [DEV-198] - Support optional sync methods along with default sharing folder method
    + [DEV-222] - support remote access for MongoDB
    + [DEV-223] - Support for Rails development with PostgreSQL's hstore extension
    + [DEV-225] - make sure apt-get-update-periodic should work

- New Feature
    + [DEV-9] - multiple python versions on python_dev VM
    + [DEV-23] - Use tox for testing
    + [DEV-139] - Add support to install phpMyAdmin
    + [DEV-146] - IDE running with vagrant
    + [DEV-155] - Add option to specify preferred ubuntu repository mirrors


- Task
    + [DEV-11] - useful sublimetext plugins and preferences configuration
    + [DEV-92] - Config support for VM customize
    + [DEV-96] - write docs how to use jira client on toolchain section
    + [DEV-98] - update workflow: git branching off section
    + [DEV-103] - update manual installation for dev
    + [DEV-119] - upgrade Gemfile and Berksfile
    + [DEV-124] - Update Workflow
    + [DEV-127] - Add "gulp" as global npm to install by default
    + [DEV-132] - add more vm_forwarded_ports config
    + [DEV-137] - Install some PHP applications to teracy-dev to make sure it works (wordpress, drupal, etc)
    + [DEV-138] - Fix violations foodcritic of apache recipe
    + [DEV-141] - update docs for v0.4.0
    + [DEV-142] - Upgrade and define the supported vagrant, virtualbox versions for v0.4.0
    + [DEV-144] - Write documentation how to develop chrome extenstion, firefox add-on with teracy-dev
    + [DEV-150] - upgrade default git from v2.0.0 to v2.2.1
    + [DEV-152] - Add `compass`, `foreman` to default global gems
    + [DEV-158] - upgrade cookbooks to latest stable versions
    + [DEV-170] - update automatic installation scripts
    + [DEV-172] - use default memory setting of vagrant instead of current 2048
    + [DEV-175] - Set default VM memory is 512MB instead of default 318MB
    + [DEV-180] - update the docs copyright year on the footer
    + [DEV-194] - update documentation how to use restview for .rst writing
    + [DEV-227] - release teracy-dev v0.4.0



[0.3.5][] (2014-12-28)
----------------------

bug fixes and improvements

- Bug
    + [DEV-116] - problems related to virtualbox guest addition
    + [DEV-154] - 'open_loop': redirection forbidden caused by berkshelf


- Improvement
    + [DEV-156] - Add options to specify base box version



[0.3.4][] (2014-09-18)
----------------------

bug fixes

- Bug
    + [DEV-116] - problems related to virtualbox guest addition
    + [DEV-121] - No "source" of install_method for mongodb recipe


[0.3.3][] (2014-09-05)
----------------------

provide teracy/dev basebox v0.3.3 with 64 bit

provide teracy/dev-all basebox v0.3.3 with 64 bit and all options enabled


- New Feature
    + [DEV-100] - Provision Ubuntu 12.04 64bit instead of 32 bit


- Task
    + [DEV-108] - Create dev-all base box



[0.3.2][] (2014-07-28)
----------------------

bug fix on windows: .virtualenvs permission denied

- Bug
    + [DEV-109] - permission denied of .virtualenvs on windows


[0.3.1][] (2014-07-22)
----------------------

bug fixes to reduce provision time and make sure nosetest works well.

- Bug
    + [DEV-101] - nosetests does not work well on vagrantbox

- Improvement
    + [DEV-99] - Reduce the provision time of base box v0.3.0 on v0.3.0


[0.3.0][] (2014-07-16)
----------------------

The next milestone release includes:

- Use teracy base box
- Support overriding vagrant configuration that is ignored by git
- Update workspace layout: `workspace/personal` and `workspace/readonly`
- Bat script to install virtualbox and vagrant automatically for Windows
- More dev platform support: Ruby, Node.js, Java, PHP
- Database support: mysql, mongodb, postgreSQL
- docs updated

Details:

- Bug
    + [DEV-6]  - vm.ssh.forward_agent does not work on windows host
    + [DEV-63] - failed to vagrant up at child directory of teracy-dev
    + [DEV-75] - Fix Doc Syntax Error
    + [DEV-81] - update code.teracy.org instead of teracy.com to ssh known hosts
    + [DEV-93] - virtualenvwrapper not work

- Improvement
    + [DEV-7]  - Don't mess custom configuration into managed versioned file
    + [DEV-45] - automatic docs deploy of 0.2.0 instead of v0.2.0
    + [DEV-57] - Update workspace layout
    + [DEV-60] - Vagrant Config override instead of overwrite
    + [DEV-62] - Update some vagrant config attributes
    + [DEV-64] - warning when vagrant_config_override.json is malformed
    + [DEV-65] - Support deep key override
    + [DEV-77] - Make sure consistent recipe file names (use _ instead of -)
    + [DEV-80] - Make sure git usage from vagrant box and host work well together
    + [DEV-82] - Add support for ruby.globals
    + [DEV-84] - Support ruby.version config
    + [DEV-88] - Support apt package installer configuration

- New Feature
    + [DEV-49] - node.js dev support
    + [DEV-56] - Create .bat file to install vagrant and virtualbox automatically on Windows
    + [DEV-61] - Support PHP
    + [DEV-85] - Support mongodb
    + [DEV-86] - Support mysql db development
    + [DEV-87] - Support postgreSQL development

- Task
    + [DEV-47] - review and update docs
    + [DEV-51] - Improve and Create visual guide for workflow
    + [DEV-54] - Upgrade support for vagrant and virtualbox
    + [DEV-55] - Create Teracy base boxes for v0.3.0
    + [DEV-59] - install "bower" by default for node.js support
    + [DEV-66] - upgrade git
    + [DEV-69] - Upgrade npm for teracy-dev
    + [DEV-71] - Update docs to make sure it's the most up to date
    + [DEV-72] - remove known_hosts file
    + [DEV-73] - remove system-python recipe


[0.2.0][] (2013-11-20)
----------------------

The next milestone release: extend CHEF, better support for python platform development

- Migration from v0.1.0 to v0.2.0
    + Vagrantfile: https://github.com/teracy-official/dev/commit/f8906c9d5d24951028a41f524e68463ea0bf32f8

- Sub-task
    + [DEV-25] - Define Python Coding Standards

- Bug
    + [DEV-5] - Bug when determining ubuntu

- New Feature
    + [DEV-31] - extend CHEF
    + [DEV-39] - Make sure gettext is available on demand
    + [DEV-42] - optional add pip index-url of teracy's public pypi

- Task
    + [DEV-1] - Project migration
    + [DEV-14] - define software semantic versioning
    + [DEV-16] - update the latest development of sphinx-deployment
    + [DEV-17] - update docs, resources after github issues migration
    + [DEV-18] - update workflow
    + [DEV-19] - update project-template
    + [DEV-20] - release process documentation
    + [DEV-22] - upgrade setuptools to 1.0
    + [DEV-26] - add interesting resources section
    + [DEV-28] - upgrade vagrant
    + [DEV-30] - use nature theme for docs instead of default one
    + [DEV-35] - upgrade to sphinx-deployment v0.2.0


[0.1.0][] (2013-08-17)
----------------------

Release the first milestone

- Sub-task
    + [DEV-2] - release current deprecated teracy-dev to be 0.1.0

[0.1.0]: https://issues.teracy.org/secure/ReleaseNote.jspa?projectId=10400&version=10000

[0.2.0]: https://issues.teracy.org/secure/ReleaseNote.jspa?projectId=10400&version=10002

[0.3.0]: https://issues.teracy.org/secure/ReleaseNote.jspa?projectId=10400&version=10702

[0.4.0]: https://issues.teracy.org/secure/ReleaseNote.jspa?projectId=10400&version=11000

[0.4.1]: https://issues.teracy.org/secure/ReleaseNote.jspa?projectId=10400&version=12200

[0.4.2]: https://issues.teracy.org/secure/ReleaseNote.jspa?projectId=10400&version=12201
