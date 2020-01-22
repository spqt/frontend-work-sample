<p align="center"><img src="https://sp-cdn.mytaste.org/images/logo-full.svg?v=197" height="50px"></p>

## Frontend Work sample
This test is conducted to see how you write frontend code.


#### The assignment
In this assignment we would like you to build a DataTable displaying all of the James Bond movies.  

##### Part 1
1) You need to create a DataTable with the data from the ***movies.json*** file
2) On the list view, you should have the following fields `title`, `year`, `actor` 
3) The default sorting on the datatable should `year high-low` 
4) The movies should be paginated with `10` movies per page
5) When clicking on a row in the DataTable, a modal should appear showing all the available data for the movie

##### Part 2
1) Style your DataTable and pages with SCSS and compile it with gulp.
2) Minify your compiled gulp tasks

##### Restrictions
No restrictions

##### movies.json
This .json file contains all the James Bond movies and its data and properties are listed below.
   
   ```
    {
      "movies": [
        {
          "title": "Skyfall",
          "year": 2012,
          "actor": "Daniel Craig",
          "director": "Sam Mendes"
        },...
   ```