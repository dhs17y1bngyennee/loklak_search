# loklak_search

[![Build Status](https://travis-ci.org/fossasia/loklak_search.svg?branch=master)](https://travis-ci.org/fossasia/loklak_search)
[![Join the chat at https://gitter.im/loklak/loklak](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/loklak/loklak)
[![Code Climate](https://codeclimate.com/github/fossasia/loklak_search/badges/gpa.svg)](https://codeclimate.com/github/fossasia/loklak_search)
[![codecov](https://codecov.io/gh/fossasia/loklak_search/branch/master/graph/badge.svg)](https://codecov.io/gh/fossasia/loklak_search)
[![Dependency Status](https://gemnasium.com/badges/github.com/fossasia/loklak_search.svg)](https://gemnasium.com/github.com/fossasia/loklak_search)

The loklak_search creates a website using the loklak server as a data source. The goal is to get a search site, that offers timeline search as well as custom media search, account and geolocation search.

In order to run the service you can use the API of http://api.loklak.org or install your own loklak server data storage engine. [loklak_server](https://github.com/loklak/loklak_server) is a server application which collects messages from various social media tweet sources, including twitter. The server contains a search index and a peer-to-peer index sharing interface. All messages are stored in an elasticsearch index.

A sample site of this repo is deployed on the GitHub gh-pages branch and automatically deployed here: http://loklak.fossasia.org

---

## Communication

Please join our mailing list to discuss questions regarding the project: https://groups.google.com/forum/#!forum/loklak

Our chat channel is on gitter here: https://gitter.im/loklak/loklak

## Installation

There is no 'installation' process for loklak_search, it consist of web pages which must work in a local environment, hosted in the file system and hosted as github pages as well. This repository will host the pages as github pages.

## Technology Stack

### Components
* HTML - Structure of the web page generated.
* CSS - Styling options and details ofthe web page.
* Javascript(JSON) - Used to store information for deploying the application such as dependencies.
* Angular2 - Structure for deployment of the web page.

## Services and Dependencies

### Bower

The goal is to use [Bower](http://bower.io) to manage front-end dependencies in future.

### Loklak Server
See here to run your own https://github.com/loklak/loklak_server (recommended), and change `apiUrl` in config accordingly. Last resource, or for production is `http://api.loklak.org

## Contributions, Bug Reports, Feature Requests

This is an Open Source project and we would be happy to see contributors who report bugs and file feature requests submitting pull requests as well. Please report issues in the GitHub tracker.

## Branch Policy

We have the following branches
 * **master**
	 All development goes on in the master branch. If you're making a contribution,
	 you are supposed to make a pull request to _master_.
	 PRs to the branch must pass a build check and a unit-test check on Travis
 * **gh-pages**
   This contains the autogenerated code of the master branch that is generated by Travis.

## License

This project is currently licensed under the The MIT License (MIT). A copy of LICENSE.md should be present along with the source code. To obtain the software under a different license, please contact FOSSASIA.
