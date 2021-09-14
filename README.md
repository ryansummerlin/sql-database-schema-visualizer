# Practice: SQL Relational Database Schema Visualizer

In this practice, you will use an online tool to create a diagram for a simple
relational database.

## Getting started

Before you begin, go to [dbdiagram.io]. Click "Create a diagram" (or the
equivalent button to open the application). Find the "Sign in" button (upper
right), and login using your *GitHub* account. (If this is your first time using
this tool, you will need to create an account.)

Next, click the "? Help" button in the upper right of the diagram application.

Read through the instructions to learn how to

* Specify a table
* Define a relationship

## Make your first diagram

Type code into the left panel to create a "kids" table with three fields

* `id` - number and the primary key
* `name` - string
* `age` - number

Next, create the table "toys" containing

* `id` - number and the primary key
* `name` - string
* `kid_id` - number (so it matches the `id` in the `kids` table)

Then, set up a relationship reference so the `kid_id` field in the `toys`
table connects to the `id` field in the `kids` table.

Finally, drag the tables around in the diagram area to make them easy to read
and understand the relationship.

## Check your work

The result should look something like this:

![result]

## Continue exploring

Take the remaining time to add more fields, tables and relationships. Drag the
tables around in the diagram to make it look nice.

Here are a few suggestions to get your started. Please come up with more or
different options on your own!

* Manufacturer for each toy (one manufacturer can make many toys)
* Purchase date for each toy
* Parents of each kid (each kid has up to two parents, each parent can have
  multiple kids)
* Current school for each kid, grade in that school would be nice to include
* Teacher or teachers for each kid, and the school where each teacher works
* Consider: What is the value in relating kids directly to schools, when they
  are indirectly related through their teacher(s)?

Be creative! As you work, discover what questions you have so you can bring them
to your instructions during your next discussion.

> Tip: Write down questions as you have them while you are problem-solving. If
> you get a solution, you can cross them off your list of ones to ask, and
> perhaps you'll find that others had the same or similar questions too!


[dbdiagram.io]: https://dbdiagram.io/
[result]: https://appacademy-open-assets.s3.us-west-1.amazonaws.com/Modular-Curriculum/content/module-04/week-10/practices/sql-diagram-practice-kids-toys.png