# Songr Spring Boot 

This project is implemented using **spring boot** application.
It is made as a music library to get albums data to enjoy whenever you want.
To run my application open your browser on `localhost:8080` , now you are in the home page .  
next you can go to the following routs :
- `/hello ` which is going to take you to hello page which is going to greet you. 
- `/hello?name=yourName` which is going to take you to hello page and greet you by your name.
**Example**: if you went to `localhost:8080/hello?name=bara'ah`   
  you will get Hello bara'ah !.
- `/capitalize/{name}` which is going to take you to capitalize page and capitalize what you have specified in the name colored in red.  
**Example**: if you went to `localhost:8080/capitalize/bara'ah`   
you will get bara'ah capitalized => BARA'AH (red colored).
- `/album` which will take you to album page that will show you an album in JSON format. 
- `/albums` which will take you to albums page and show you a list of albums in JSON format. 
------------------------------------
## version 2  
***
To use this version of my project you have to create a table in your database , my table called `album`.  
Then update your application.properties : your username and database name.  
Now you can go to the home page `localhost:8080/`and enjoy reviewing the albums in the site.  
You can also add your albums , check for their details and add songs to them and review the whole album with its songs.
You can also view whole songs available in the website. 
