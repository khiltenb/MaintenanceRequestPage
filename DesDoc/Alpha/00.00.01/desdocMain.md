 # Design Document - Overall Design
As stated in the readme file, this is a website addition that will allow users (company staff and all equivalents therein) to request maintenance work through an online work request form. The design documents here and moving forward will restate the following, modified as the priorities change over time, as well as the intention of how the problem will be solved.
Alpha versions will live in the dev branch, betas will live in the pre-release branch, and release versions will live in the release or main branch. Each pull request should signify the following: a new alpha, a transition from alpha to beta, a new beta, or a transition from beta to release.

The client requestor side shall include the following:
 - Identifier
 - Location
 - Work type
 - Deadline
 - Level of importance

The Server side shall include the following:
 - Time request was made
 - Schedule of work
 - Logging job status
For the future, the server side may incorporate the following features:
 - job election/delegation
 - Logging of job type and frequency
 - Schedule of jobs to be done by specific employee
 - Data tracking and prediction

The administrator side shall include the following:
 - List of workers currently working, and what jobs they have lined up
 - ability to delegate or remove jobs from a worker's queue
 - access to log of jobs requested and jobs completed
The admin side may include the following at a later date:
 - Access to data tracking and prediction of jobs needing to be done

The worker's client side shall include the following:
 - A list of jobs needing allocation
 - ability to request multiple workers on one job
 - list of jobs in their queue
 - ability to mark a job in progress or completed
 - see a list of jobs done by themselves


This is by no means a comprehensive list, and will be adjusted as time reveals the needs of those that this project is intended to serve.

