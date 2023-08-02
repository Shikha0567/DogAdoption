FrontEnd code for Take-Me-Home in react Typescript

## Getting started

This repo contains the Frontend-Code for Take-Me-Home application which is a dog adoption application.
- To run the project in local Please do npm i if your using for first time,
  followed by "npm run"
- If your not running it for first time then use "npm run" to start the project

## Features:

1. The entry point of the application is login screen which authenticates the user based on username and email address. Both the fields are kept mandatory and also email format check is implemented.

2. Once the user logs in successfully, There would be two subsequent API calls made to fetch all the dogs id and then to fetch the dogs data from the id.

3. Result fetched is paginated for better user experience.

4. Upon selecting the dog by clicking on heart icon and then clicking on "generate match" button, an API call will be made to fetch the perfect match for the user.

5. Upon finding the successful match, user can check the location details of the matched pet and also he can go back and select another dogs to generate new match.

6. When no match is found, appropriate error message is display on the popup window and a button is presented for the user to try again.

7. In the sidebar, there are filter options added to filter by breed, zipcode, min age and max age of the pet and also an option to clear the filter is added.

8. If user wishes to logout, he can click on the avatar icon in the header and click on login.

