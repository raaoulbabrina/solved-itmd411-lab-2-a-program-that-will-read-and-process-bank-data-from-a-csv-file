Download Link: https://assignmentchef.com/product/solved-itmd411-lab-2-a-program-that-will-read-and-process-bank-data-from-a-csv-file
<br>
<strong><em> </em></strong>

<strong>PROJECT     </strong><strong>Bank record generations                                                </strong>

<strong><u>Objective</u></strong><strong>        </strong>To write a program that parses and processes bank data from a file.

<strong><em>PROJECT DESCRIPTION</em></strong>

Bank of IIT has gotten their hands on some interesting data which will allow for possible loans to various clients from various regions.

Accompanying the labs specs is a csv (comma separated value) file named

<strong>bank-Detail.csv</strong> which contains valuable raw data to allow the bank to process loans based on client details from the file.

You need to <u>parse</u> the data and print record data for future loan considerations.

<strong><em>Project Details</em></strong>

-Create an <u>abstract</u> class called <strong>Client.java</strong> to allow for three abstract methods the bank needs to process. Name your methods readData(), processData() and printData(). No arguments are needed for your methods.

-Create a <strong>BankRecords.java</strong> file which will <u>utilize</u> the Client asbtract methods and generate ultimately the client records from the <strong>csv</strong> file.

The client file has the following <u>header</u> / <u>field</u> <u>data</u> information

id {string}

age {numeric}

sex {FEMALE,MALE}

region {INNER_CITY,TOWN,RURAL,SUBURBAN}

income {numeric}

married {NO,YES}

children {0,1,2,3}

car {NO,YES}

save_act {NO,YES}

current_act {NO,YES}

mortgage {NO,YES}

pep {YES,NO}




Create <u>instance</u> fields with appropriate data types for each header item above in your

class. Include getter and setters for <u>each</u> instance field.

<ul>

 <li>Include code definitions for each method <em>declared</em> in your Client class as follows</li>

</ul>

Your <strong>readData()</strong> method should read in all the record data from the csv file in your

path into an ArrayList.

Your <strong>processData()</strong> method should take all the record data from your ArrayList and    <u>add</u> the data into each of your instance fields via your setters. Use an array of objects to store record data for each instance field.

Your <strong>printData()</strong> method should print the <u>first</u> 25 records for various fields to the console via your getters. Print records for the following fields:

ID, AGE, SEX, REGION, INCOME, and MORTGAGE.


