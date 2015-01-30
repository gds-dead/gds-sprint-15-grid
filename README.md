# gds-sprint-15-grid
Sprint 15 grid - 12 x 12 data grid for use at BFI

http://gds-matrix.herokuapp.com/

## What is it

It's a little Node / Express app that gathers (and then polls) data from the GOV.UK performance platform.

### Getting started

Make sure you have Node, NPM, Grunt, Bower installed.

For the time being, packages are in this repo. So at the moment it's a case of ```grunt``` in the project directory.

### The offline version

```grunt offline``` will package up the app in a single html file. It will use _yesterday's_ realtime data.

==========

### Hard-coded data

Items to check and update, because they are currently hard coded.<br>
To do: make these dynamic.

GOV.UK visitors last week<br>
https://www.gov.uk/performance/site-activity/site-traffic

Register to vote user satisfaction<br>
https://www.gov.uk/performance/register-to-vote/user-satisfaction

Carers allowance user satisfaction<br>
https://www.gov.uk/performance/carers-allowance/user-satisfaction

Prison visits by device<br>
https://www.gov.uk/performance/prison-visits/device-type

Patent renewals digital take up<br>
https://www.gov.uk/performance/renew-patent/digital-takeup

GOV.UK visitors by device<br>
https://www.gov.uk/performance/site-activity/device-type

Service assessment pass rate<br>
https://www.gov.uk/performance/digital-by-default-service-assessments/service-assessment-pass-rate

SORN digital take up<br>
https://www.gov.uk/performance/sorn/digital-takeup

### Sprint 15 facts

There are also 3 facts hard coded for Sprint 15 on 3rd February 2015

Apply for Carer’s Allowance<br>
49% of questions removed

GOV.UK Verify<br>
20,000 sign-ins

Digital self-assessment<br>
1 million registered users
