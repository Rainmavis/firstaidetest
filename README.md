# FirstAide-Web [![Build Status](https://travis-ci.com/Rainmavis/firstaidetest.svg?branch=develop)](https://travis-ci.com/Rainmavis/firstaidetest)


![Heroku](https://heroku-badge.herokuapp.com//?app=still-temple-60379)

### Abstract 
This repo is used as a test environment for the First Aide application web (orginal project can be found in https://github.com/systers/FirstAide-web).


### Rules for Contributing
1. To find possible errors for the different modules.
2. To check, correct and document each defect and report it to the test team.


### Initial Setup and Installation
To contribute for this project, you can clone it:

`$ git clone https://github.com/Rainmavis/firstaidetest`

Or download the ZIP file from above

### Test Environment Features
#### Database: 
CLEAR DB (https://www.cleardb.com/) at Google Cloud Platform

Info of Service Plan: 

1. **Database Size:** up to 10MB
2. **Connections:** up to 5
3. **Performance:** Low
4. **Masters:** 3
5. **Unit memory:** Shared
6. **Entrypoints:** 1

- MySQL 5.5
- Daily backups
- 90 day free evaluation period.

ClearDB's Database-as-a-Service (DBaaS) at Google Cloud Platform provides: Native, Unaltered MySQL, Fully Managed, Instant Deployment, Multiple Maters, Sub-second Automatic Failover, Multi-Regional Deployments, Instant Scaling, Scalability, Self Healing Technologies, Automatic Patching, Flat Rate Monthly Billing, Automated Backups, User-Initiated Snapshots, SSL Wire-Level Encryption, Automatic Backups Encryption, 40 to 50 max concurrent connections/Master.

More info: https://w2.cleardb.net/google/

#### Deployment at Heroku

PHP and Composer is installed locally.

- PHP 7.2.12 (cli) (buildt: Nov 8 2018 05:12:43) (NTS)
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies with Zend OPcache v7.2.12, Copyright (c) 1999-2018, by Zend Technologies.

- Composer version 1.7.2 2018-08-16 16:57:12

- Git version 2.17.1

1. **Heroku Git URL**  https://git.heroku.com/still-temple-60379.git
2. **Slug Size:** 17.7 MiB of 500 MiB
3. **Stack:** heroku-18
4. **Region:** United States
5. **Buildpack:** heroku/php
6. **Domain** https://still-temple-60379.herokuapp.com/

##### Resources

web vendor/bin/heroku-php-apache2

#### Tests

 1. **Unit tests:** Phpunit version higher than 6.1
