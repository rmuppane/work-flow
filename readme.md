# Process

Using this example to explain the User Assignment groups.

There are two user tasks (Assignment 1 & Assignment 2) in this example.

![process](images/process.png)<br />


# Assignment1 Group calculation

Assignment 1 Group will be calculated by DMN Rules.

| Face Amount                 | Group		              |
| --------------------------: | --------------------- |
| Less than or Equals 100000  | treaty_lloyds_create  |
| Greater than 100000         | treaty_company_create |


![Assignment1Team](images/Assignment1Team.png)<br />


# Assignment2 Group calculation

Assignment 2 Group will be calculated by DMN Rules.

Age                     | Group
----------------------: | -------
Less than or Equals 45  | treaty_company_create
Greater than 45         | treaty_lloyds_create



![Assignment2Team](images/Assignment2Team.png)<br />
