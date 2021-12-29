# Senior Backend developer assignment


This document contains description and requirements for assignment for Backend developer positions on Spokn.

Goal

1. Verify the applicant's ability to learn and practice new technology so quickly.

2. Verify the applicant’s ability to write clean and testable code.

3. Check for best practices inside the chosen backend framework.

## Requirements

Head to Google Cloud platform and subscribe for a free account to allow you to make the following:
Start your own K8s cluster with High availability, do the initial setup to expose the following services over public IPs.
Install the following:
Influx DB inside the cluster
Cassandra DB using statefulsets
Build microservice(s) that:
Scrapes the information of value of All currencies every second from (https://prices.org/) and send the information to Google Pub sub, this is using Google functions or any other way you like
Pulls prices from Google PubSub and write it to influx as measurements that allow you to sketch a graph of historical prices
Front-end that show a day view of the past 24 prices
expose the front-end on a public IP and push the code to Github repo.


## Specification

Use any Node.js framework you want or no framework at all, it's up to you. Usually we use Express.js ‑ feel free to use this one, if you don't have any preferred one.
Don't bother with any graphics, just simple HTML, simple form, no CSS needed. Or just use Twitter Bootstrap.
Be careful with Consumer-producer problems that could happen when have a massive writes into Influx
Cover code with unit tests.
Don’t over engineer things :)

## Quality requirements

Similarly, as during any other code review in our team, we'll be checking the following:

- Code quality
- APIs Design
- Usage of the configuration files
- Usage of the unit tests
- Naming convention

