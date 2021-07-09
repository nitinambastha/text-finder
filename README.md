# Introduction
text-finder is an application developed using the Spring-Boot framework, to find text provided by user in a hard coded string.

#Prerequisites :
Java 11
Gradle 6 or above

#Request :
The application receives request as GET with the search term pass as path param
Sample Request : 
http://localhost:8080/find/surprise

#Response :
The application calculates the number of occurrences of given search term and returns back in JSON in the below format 
{
 "searchText":"surprise",
 "numberOfOccurrences":6
}

#Scope
The current scope is to search only words in a given sentence. 
But it can be scaled in order to alter the sentence or to search a array of characters.


#JUnit
The service layer is currently covered in JUnit and can be found under src/test/java
