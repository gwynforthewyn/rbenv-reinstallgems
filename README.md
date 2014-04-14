## Welcome to rbenv-reinstallgems

## Installation

Simply clone the repository into the plugins directory:

    
    git clone https://github.com/jamandbees/rbenv-reinstallgems.git ~/.rbenv/plugins/rbenv-reinstallgems


## Getting Started

To run:

    rbenv reinstallgems fromversion

## What Does This Script Do?

The script cds into the appropriate, existent GEM_HOME directory for the version of ruby that you request, and then generates a GEMFILE in /tmp/ that can reinstall those gems.

Right now, it unfortunately doesn't deal with dupes in the gem list, so there's some manual editing of the Gemfile necessary. It's an improvement over doing this by hand, though!