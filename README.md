This is a fork from the [show-job gem](https://github.com/binarygit/show-job) by Avii.
I made a quick and dirty update to format the result of Avii's algorithm into bullet-points and to have it be copied to the clipboard automatically to help me make my weekly Ruby on Rails jobs mega thread I share on LinkedIn.

I disabled all options. Instead, it will list all jobs found for:
* Worldwide remote jobs
* USA remote jobs
* South America remote jobs

This is a very simple script. If you want to use it, you can just clone this repo and run show-job file from the command-line: `ruby show-job`

Below is the Docs for the original [show-job gem](https://github.com/binarygit/show-job)
# show-job

## Installation

```
gem install show-job
```

-----

The `show-job` program displays Ruby/Ruby on Rails jobs right in your command line!
It pulls jobs from __seven__ different prominent Ruby job sites. The sites are:
1. [Gorails](https://jobs.gorails.com/)
2. [Weworkremotely](https://weworkremotely.com/)
3. [Ruby on Remote](https://rubyonremote.com/)
4. [Ruby on Rails jobs](https://www.ruby-on-rails-jobs.com)
5. [Rails Hotwire Jobs](https://railshotwirejobs.com/)
6. [WeAreHiring](https://wearehiring.io/)
7. [Rails Job Board](https://jobs.rubyonrails.org/)

Command line usuage summary:
```
Usage: show-job [options]
        --ww                         Display only worldwide jobs
        --senior                     Display only senior jobs
        --us-only                    Display jobs only for the United States
        --no-us                      Display jobs for places other than United States
```

## Usuage

### Using the --ww flag
![ww](https://github.com/binarygit/show-job/assets/87677429/70b96552-3a2c-4c11-acb1-6473874f990c)

### Using the --senior flag
![senior](https://github.com/binarygit/show-job/assets/87677429/00bba748-f030-4221-9a6f-256a28bfe20c)

### Using the --no-us flag
![no-us](https://github.com/binarygit/show-job/assets/87677429/8dd92d26-7479-4949-99fc-bcf2b13a9b9c)
