## Exercise 1:
Create the following scenario in POCO classes.

An Organization
- Has a name, phone number, address and a collection of employees

An Employee
- Has a first name, last name, email, and title.

An employee can be belong to one organization.

# Code Exercises
- Clone the repo: https://github.com/Codagami/Interview.CSharp.git
- Create a new branch
- Walk through the following 2 exercises

## Exercise 2:
Inside the SimpleRepository, there is an interface defined.

Implement the interface within that file.

## Exercise 3:
Create an Organizations controller with a list and a detail action.

For the list view, use OrganizationListVM as the Model to create a table with
all the organizations returned.  Include a link to the details view that will
show the organization's details.

For the detail view, show all the properties of the organization at the top of
the page and then below that, show a table with all the employees of that organization
and all their properties.