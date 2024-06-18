<h1>Apply more filters in SQL</h1>


<h2>Description</h2>
In this lab activity, you’ll apply operators to accurately filter for specific numbers and dates!

<h2>Environments Used </h2>

- <b>MariaDB shell</b>

<h2>Scenario:</h2>

In this scenario, you’re investigating a recent security incident.

You need to gather information about login attempts for certain dates and times. This will help in resolving a security incident.

Here’s how you’ll do this task: 

<b>First</b>, you’ll retrieve login events made after a certain date. 

<b>Second</b>, you’ll narrow the focus of the search to filter logins in a date range. 

<b>Third</b>, you’ll investigate logins that were made at certain times. 

<b>Finally</b>, you’ll filter login attempts based on their event IDs.

It's time to get started and use operators to filter data from a table!


<h2>Tutorial walk-through:</h2>

<h3>Task 1. Retrieve login attempts after a certain date</h3>

In this task, you need to investigate a recent security incident. To do this, you need to gather information about login attempts made after a certain date.

1. Complete the SQL query to retrieve data for login attempts made after '2022-05-09'. Replace X with the correct operator:

<img src="https://i.imgur.com/klhOB4v.png" height="80%" width="80%"/>

<b>Now</b>, based on your first query, you find a need to expand the date range to include 2022-05-09 in your search.

2. Complete the SQL query to retrieve data for login attempts that were made on or after '2022-05-09'. Replace X with the correct operator:

<img src="https://i.imgur.com/pK59urp.png" height="80%" width="80%"/>



<h3>Task 2. Retrieve logins in a date range</h3>

In this task, you need to narrow the focus of the search. Login attempts made after 2022-05-11 shouldn't be included. Use the BETWEEN and AND operators to return results between '2022-05-09' and '2022-05-11'.

Run the query to retrieve the required records. You must insert the required dates X and Y:

<img src="https://i.imgur.com/cDGpFXb.png" height="80%" width="80%"/>


<h3>Task 3. Investigate logins at certain times</h3>

In this task, you need to investigate logins that were made at certain times. To do this, filter the data in the log_in_attempts table by login time (login_time).

<b>First</b>, your organization's typical work hours begin at 07:00:00. Retrieve all login attempts made before 07:00:00 to learn more about the users who are logging in outside of typical hours.

1. Write a SQL query to retrieve data for login attempts made before '07:00:00'.

<img src="https://i.imgur.com/CdrsQjD.png" height="80%" width="80%"/>

The query in the previous step returned more results than required.

2. Modify the query to return logins between '06:00:00' and '07:00:00'.

<img src="https://i.imgur.com/07hv9pZ.png" height="80%" width="80%"/>


<h3>Task 4. Investigate logins by event ID</h3>

In this task, you need to investigate login attempts based on event ID numbers. With this query, you want to return only the event_id, username, and login_date fields from the log_in_attempts table.

<b>First</b>, your organization's typical work hours begin at 07:00:00. Retrieve all login attempts made before 07:00:00 to learn more about the users who are logging in outside of typical hours.

1. Write a query to return login attempts with event_id greater than or equal to 100.

<img src="https://i.imgur.com/jqEIC0o.png" height="80%" width="80%"/>

The query in the previous step returned more data than required.

2. Modify the query to return only login attempts with event_id between 100 and 150.

<img src="https://i.imgur.com/yW240um.png" height="80%" width="80%"/>



<h2>Conclusion</h2>

You have completed this activity and practiced applying

- the WHERE keyword
- the BETWEEN and AND operators
- operators for working with numeric or date and time data types (for example, =, >, >=)

to filter data from a table.

  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
