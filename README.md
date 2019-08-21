# Overview

Template for ruby script

## Getting Started

Install bundler with `gem install bundle`.  This is ruby's package manager.
Install rubocop globally.  `gem install rubocop`

Run `bundle install` to install packages.

## Starting a new project from scratch

Run `bundle init` to initialize a Gemfile.
Initialize guard with `guard init rspec`

Run `rubocop -a` to autofix lint violations.

## To start a new project from this template

Create a zip without git tracking.
git archive --format zip --output ~/Desktop/ruby_template.zip master
Extract the zipfile into the desired project location.
