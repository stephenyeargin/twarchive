# TwArchive (Twitter Archive)

This is a rudimentary tool to generate a CSV of the most recent tweets of a given user account and save them to a CSV file. It may not grab _all_ of them because of rate limiting.

The CSV files are saved in the `output/` directory.

## Prerequisites

- Ruby 2.4 or later
- Bundler (`gem install bundler`)
- A Twitter development account + app (obtaining app credentials)

## Setup

1. Run `bundle install` to load necessary dependencies
1. Copy `.env-dist` to `.env`
1. Edit `.env` to include your app's credentials (see "Keys and tokens" tab)

## Usage

Generate an archive for Twitter user `@jack`.

```
./bin/twarchive jack
```

Open `./output/jack.csv` to review contents.
