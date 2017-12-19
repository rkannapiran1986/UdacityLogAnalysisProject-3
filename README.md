# Udacity Data Log Analysis Project - Kannapiran

## Project Requirement:
- What are the most popular three articles of all time?
- Who are the most popular article authors of all time?
- On which days did more than 1% of requests lead to errors?

## How to run the application

First you must have the PostgreSQL newsdata.sql database running from the FSND virtual machine (Use configurations shared by Udacity). Download the project in to your vagrant folder with folder name ```newsdata```

- From the 'vagrant' directory, run ```vagrant up```.
- SSH to virtual machine with ```vagrant ssh```.
- Connect to psql database with ```psql -d news```.
- Change to your vagrant root ```$ cd /vagrant```
- Change to your application directory ```$ cd newsdata```
- Run the python file to view the results ```$ python log_analysis_proj.py```
- Wait few seconds to get the results..

## Example output
```bash
##############################

Executing query to get results...

@@@@@@@@@@@@@@@@@@@@@@

Top three articles by page view:
(1) "Candidate is jerk, alleges rival" - 338647 views
(2) "Bears love berries, alleges bear" - 253801 views
(3) "Bad things gone, say good people" - 170098 views

##############################

Top three authors by view:
(1) Ursula La Multa - 507594 views
(2) Rudolf von Treppenwitz - 423457 views
(3) Anonymous Contributor - 170098 views

##############################

Days with more than 1% error:
July 17, 2016 -- 2.3% errors

##############################

```