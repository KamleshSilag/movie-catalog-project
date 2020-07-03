# movie-catalog-project

Microservice Architecture

1. Movie-Info-service<br/>
*Provides movie info when provided with movieId*<br/>
*API - **/movies/{movieId}***<br/><br/>
2. Ratings-Data-service<br/>
*Provides rating data when provided with userId*<br/>
*API - **/ratingsdata/users/{userId}***<br/><br/>

3. Movie-Catalog-service<br/>
*Provides user ratings with movie name by calling above 2 API's*<br/>
*API - **/catalog/{userId}***<br/><br/>

4. Discovery-server<br/>
*Eureka Server for serving above client services* <br/>
*Job of Service Discovery*


Course Credits - javabrains.io
