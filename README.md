## PCF Event Alerts

This repo contains the documentation for PCF Event Alerts.

**Note**: Please use PRs to contribute new content or make fixes to this PCF Event Alerts documentation.

The contents of this repo are currently published at [docs-pcf-staging.cfapps.io/event-alerts/](https://docs-pcf-staging.cfapps.io/event-alerts/).

The book file that publishes this content is at [https://github.com/pivotal-cf/docs-event-alerts](https://github.com/pivotal-cf/docs-event-alerts).

## About product name

Product name is **PCF Event Alerts**. The plugin is the **PCF Event Alerts plugin**, which users can install from pivnet.
When you are referring generically to an alert as a concept, use the term "alerts" consistently.

## About branches 

Currently, the **master** branch is for unreleased, v1.0, documentation. Make changes or PRs relevant to v1.0 on that branch.

Other branches will be created for future versions.

The above info about branches comes from Megan Moore and April 10,2018.

## First draft info 

Some questions tech writers had for PMs during the first documentation phase are summarized in [this google doc](https://docs.google.com/document/d/1aNMSYMR6rs1_gunXoBlC3qq_Uq97mMXWBiJUydGCDHw/edit?usp=sharing).

## Developing docs locally

This will make the book available at localhost:4567 and automatically update when you write changes to disk:

```
cd docs-book-event-alerts
bundle install
bundle exec bookbinder watch

```
