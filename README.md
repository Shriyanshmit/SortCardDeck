
Doc for Card sorting:

Project Structure:
API (Dot Net Core 3.1 LTS)
 
1.	Playing Card API- Dot net core 3.1 api project for exposing API endpoints to UI application
2.	Entities- Used for creating custom class
3.	Business Logic- Write the business logic to sort the card deck
4.	WEB-API-Tests- Unit test cased for API

UI Application (Angular 13): UI application is created using angular 13.

API endpoint path is set in file ~\UI\CardSortingUI\src\app\services\playing-card-service.service.ts
private url: string = "https://playingcardapi20220320130653.azurewebsites.net/api/SortCardDeck";

Possible Improvements:
1.	Custom validation on invalid card @ UI side, API implemented.
2.	Error logging in api
3.	UI improvement
4.	Layout page design can be extended
5.	More test cases for API

UI application
URL: https://carddeckui.azurewebsites.net/card-sorting-ui

API:
URL: https://playingcardapi20220320130653.azurewebsites.net/api/SortCardDeck
Type: Post
Input Data: String Array e.g. ["3C","JS","2D","PT","10H","KH","8S","4T","AC","4H","RT"]
Response: Sorted string array e.g. ["4T","PT","RT","2D","8S","JS","3C","AC","4H","10H","KH"]
Screens:
 
