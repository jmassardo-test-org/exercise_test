# exercise_test

This repo contains a prototype automation for automatically enabling branch protection rules on new repos in an org.

* Export `GITHUB_TOKEN` with a valid token with appropriate permissions
* Run `bundle install`
* Run `ruby server.rb`
* Set GH org webhook to point to appropriate FQDN/IP