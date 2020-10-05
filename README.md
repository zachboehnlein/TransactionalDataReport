# TransactionalDataReport

This project was to automate the creation of a transactional data report for a specific division. This pulls 6 weeks of their transactional data, cleans it up to their specifications and writes it back to SQL. From there a weekly pipeline triggers to pull their data, run this python databricks notebook and then from sql send it back to them so they can pick it up.  
