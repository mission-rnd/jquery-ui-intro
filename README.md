Create tab structure where there are four tabs for CRUD operations of contacts
We will provide the base html which will show the four tabs but it will not have any functionality included, meaning if the tab is clicked you don't see any change in DOM. The task of the student is to write code to display the appropriate html code when they click the tabs - TEST CASE
For example, lets say we give four html pages as part of project
create.html
read.html
update.html
delete.html

Use jquery ajax to call backend endpoints, write test cases for both success and failure from ajax front only
Write test case for showing loading icon when an ajax call is being made
For success scenario and failure scenario need test cases to check DOM.

We need to expose js placeholder functions where student will write code which will modify the DOM.
Test cases to check every jquery function we expect is being called


1 - There should be 4 tabs
2 - Check jquery.click is being called when he clicks any of the tabs
For List
3 - Check whether jquery.ajax is called with required parameters
4 - Check DOM is being updated as expected if success
5 - Check DOM is being updated as expected if failure
6 - Check DOM has loading icon when ajax call is being performed
For ADD
7 - Check DOM is loaded according to the defined pattern
8 - Check when ADD button is clicked, jquery.ajax should be called
9 - Check DOM is being updated as expected if success
10 - Check DOM is being updated as expected if failure
11 - Check if redirect happens to list page
For UPDATE
12 - Check DOM is loaded according to the defined pattern
13 - Check when ADD button is clicked, jquery.ajax should be called
14 - Check DOM is being updated as expected if success
15 - Check DOM is being updated as expected if failure
For DELETE
16 - Check when DELETE button is clicked
17 - Check whether jquery.ajax is called with required parameters
18 - Check DOM is being updated as expected if success
19 - Check DOM is being updated as expected if failure
20 - Check if redirect happens to list page
