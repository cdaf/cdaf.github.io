# Developer Guidance

Jekyll is the default static content engine used in GitHub pages. Any static content can be used, however, exploiting th default for this site.

## Ruby

Install combined Rub + DevKit

    https://rubyinstaller.org/downloads/

or user Choco

    choco install ruby --version=2.7.2.1
    choco install ruby2.devkit

Ensure the bundler matches lock

    gem install bundler:2.2.15
    
## Run a local server

Open a user session and start the jekyl server

    bundle update
    bundle exec jekyll serve

Open page http://127.0.0.1:4000/
