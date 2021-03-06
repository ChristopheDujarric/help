---

template:         article
reviewed:         2016-02-20
title:            Integrate New Relic in fortrabbit
naviTitle:        New Relic
lead:             Where should I improve the performance of my App? Learn how to combine the popular software analysis tool with fortrabbit.
group:            Extending_fortrabbit

image:            new-relic-logo.svg
websiteLink:      https://www.newrelic.com?utm_source=fortrabbit
websiteLinkText:  newrelic.com
dataCenters:      n/a

seeAlsoLinks:
    - blackfire

---

## About New Relic

[New Relic](https://www.newrelic.com) is a suite of professional software analysis tools. It offers analytics and deep insights on your Apps' performance and possible bottle necks. New Relic integrates as a PHP extension, which is installed (but not enabled) on all fortrabbit Apps.


## Usage

fortrabbit has a Bring-Your-Own-License integration with New Relic. That basically means: you need an account over at New Relic. Then you only need to paste the license key in our dashboard.

### Over at New Relic

1. Sign up or log in to [New Relic](http://newrelic.com/).
1. Add a new application
1. Copy the license key

### At fortrabbit

1. Log in to the Dashboard
1. Navigate to your App > Settings > PHP > Debugging
1. Paste the New Relic license key
1. Save the PHP Settings


## Further readings

* [New Relic BYOL integration announcement](http://blog.fortrabbit.com/new-relic-byol)