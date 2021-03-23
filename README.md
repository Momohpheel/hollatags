## About Coding Challenge

## Problem:
- An application for billing 10,000 users over a given billing API (owned by a third
party e.g. Telco/Bank).
- The billing API takes 1.6secs to process and respond to each request
- The details of the users to bill is stored in a Database with fields; id, username, mobile_number and amount_to_bill

## Requirements:
- Write or describe a simple PHP code that will be able bill all the 10,000 users
within 1hr.

## Laravel Queue: 
I made us of Laravel Queue + Redis. aravel allows you to easily create queued jobs that may be processed in the background. By moving time intensive tasks to a queue, your application can respond to web requests with blazing speed and provide a better user experience to your customers.




