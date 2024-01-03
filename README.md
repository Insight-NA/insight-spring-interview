# Insight Spring Interview App

> Basic Spring web API application.

## Instructions

1. Clone the repository and open the project in your preferred editor or IDE.
   1. If you have a Gitpod account, you may create a Gitpod workspace for this repo be opening this URL: [https://gitpod.io/#https://github.com/Insight-NA/insight-spring-interview](https://gitpod.io/#https://github.com/Insight-NA/insight-spring-interview)
2. Take a brief moment to set up the project as needed per your normal working style and tooling approach.
3. Run the application to confirm everything is setup appropriately. 
The app should start up without error using the command `./mvnw spring-boot:run` or use your own startup steps and configuration.
   * The `/hello` endpoint should return a JSON response if the application started correctly.
4. Add the classes and structures needed to enable a new API endpoint for books. 
Talk through the steps you are taking with your interviewer(s).
A book should have at least the following fields: Title, Author, Year Published.
   * Note that this project is set up to use an H2 embedded database, so it will be empty by default.
   Spring Data may be used to populate an initial schema, and you will need to provide sample data somehow.
5. Add unit tests for new classes that you create for the new API.
Tests do not need to be exhaustive, but should illustrate a good understanding of unit testing.
6. Build and run the app again to ensure the new changes are valid.
7. Use a web browser or API tool like Postman to show the new endpoint is working.

## Dependencies

* Java SDK 17
