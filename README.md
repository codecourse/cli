### The official Codecourse CLI

Access codecourse.com features directly from the command line.

___

## Current features

* `course:download [slug]` Download all videos for a course

## Requirements

* Composer (https://getcomposer.org/)
* PHP 7.1.2 or higher

## Installation (global)

<h4>macOS</h4>

```
composer global require codecourse/cli
```

Make sure you add Composer's global vendor/bin folder to your `$PATH`. You can do this by adding `PATH=$PATH:~/.composer/vendor/bin` to your `~/.bash_profile` file and run:

```
# source ~/.bash_profile
```

## Installation (standalone)

Download the `codecourse` binary from this repository and run:

```
# cd /path/to/downloaded/binary
# php codecourse
```

## Known issues

* The Codecourse CLI has not been tested on Windows/Linux platforms yet.

## Usage

Once installed, run `codecourse` for a list of available commands.

## Support

If you're having trouble setting up the CLI, email hello@codecourse.com or alex@codecourse.com