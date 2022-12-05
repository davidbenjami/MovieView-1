# MovieView-1
Cosc 338 Mobile App Development

Project Name: Final Project ‘Movie Views’

David Bogunjoko-Benjamin and Brad Obi

Our app basically is designed to have data persistence. The app will make API calls to the IMDB website which will show the ‘Top 100 movies’.  We plan to create a local database of our app in Kotlin; use features from our labs and the previous unit projects (especially project 4,5 and 6). The user will be given access to search a specific movie they like or dislike within the app as well.

Features Used:
Database- create instances and class to hold data, the main access point to the cached data; 
Entity- specifies column and creates a template for each row in future database;
DAO (data access objects)- take the fetched data and insert into a table to be displayed and clear out all older entries;
Kotlin file- common data class language being used to create data class;
Fragments- to look at a specific image of the website page;to navigate through the app 
Article Search- query for specific movie data from cached api data form the website;
Single source of truth/ data- the main activity file that displays only items from the database such as a parsedJson function;
RecyclerView - display the list of movies in a designed pattern;
Use glide to retrieve information that is being searched, the context will have the media imageurl 

App Structures:
Kotlin for Android studios Android mobile device/ phone or tablet; 
Room Library- data persistence by saving data to local storage and display cache data;
SQLite- local database along with ‘Room Library’ to store and load cached data.



Who did what? 
We did research on the different features to implement and how to implement them will affect our app.
