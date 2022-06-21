# SQL_case_study1
## Airlines

### This is a simple postgresql practice. 

**Step 1:** 
You should first create three tables named: airlines, planes and sold_seats and their corresponding columns as follow: 
1. airlines
   - airline_id *(primary key)*
   - plane_id
 
2. planes
   - plane_id *(primary key)*
   - number_of_seats
 
3. sold_seats 
   - airline_id
   - seat_num

**Step 2:** 
Information (entities) about each table is provided where we can use **INSERT INTO** syntax to add rows. 

**airlines**

| airline_id | plane_id |
| --------- | ----------|
| 211 | 128 |
| 870 | 157 |
| 200 | 23 |
| 211| 23|

**planes**

| plane_id | number_of_seats|
| ---------- | --------- |
| 128 | 5 |
| 23 | 7 |
| 157 | 4 |
| 239 | 2|

**sold_seats**
| airline_id | seat_num |
| ---------- | --------- |
| 211 | 1 |
| 23 | 7 |
| 157 | 4 |
| 239 | 2|



**Task:** 
  To find number of seats that are not sold for each airline. 
