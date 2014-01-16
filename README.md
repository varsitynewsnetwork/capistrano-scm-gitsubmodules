# Submodules for capistrano 3

# WARNING: Deprecated

This module has been deprecated with capistrano 3.1.0. Try this instead: https://gist.github.com/stevenscg/8176735

## Installation

Add this line to your application's Gemfile:

    gem 'capistrano-scm-gitsubmodules'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install capistrano-scm-gitsubmodules

## Usage

    set scm: 'gitsubmodules'

This wil make capistrano require the tasks.

## Notes

This gem replaces the archive technique with a clone. So release folders will be clones of the repo folder, instead of just plain files, similar to capistrano 2.
