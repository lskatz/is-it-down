# Contributing

To contribute, please be familiar with GitHub Actions.
Documentation here: https://docs.github.com/en/actions/quickstart

To contribute, make a fork of this repo and create a separate branch.
When it is working, send a pull request to this repo.

## General guidelines

* Each separate service should be in its own yml file.
* If a service has many different major queries, then please split those services to their own separate yml file.
* Do not overload the target website or API. Try to be minimalistic.
* Try to have quick tests. Avoid a test that itself runs for more than a minute. Understandably some steps like `apt` will take up that time and it should not count against your time.

