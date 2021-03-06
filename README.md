# News-App
Android news app built in kotlin that fetches news data from <a href="https://newsapi.org/">news api</a> with **Retrofit** and displays news to users.
This App follow MVVM architecture carrying Room operations in Data Access Objects(DAO) and API calls in Repository, and fragments navigations implemented with Android Navigation Component.

### Problem Statement : 
In Today's corporate life, people don't have enough time to watch news from different sources, thus they can miss out important opportunities, information, etc. Besides opportunites, it's a good habit to be educated about the environment we live in.

### Proposed Solution : 
A News app built in kotlin with implementation of MVVM architecture and android navigation components.This news app clusters news from various sources of journalism, So that users can get aware in a glimpse. They can also share relevant news with their belongings and save important news.


 ### App Screenshots : 
 
 <table align="center">
  <tr>
    <th>News</th>
    <th>Saved News</th>
    <th>News Sharing</th>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/79650580/148635903-616783b2-7a1d-4630-8dba-c2d4464ab322.jpg" alt="News Display" style="width:250px;height:500px;"></td>
    <td><img src="https://user-images.githubusercontent.com/79650580/148636163-39cc92db-8472-4129-b720-a247f40dc998.jpg" alt="Saved News" style="width:250px;height:500px;"></td>
    <td><img src="https://user-images.githubusercontent.com/79650580/148540369-f782a187-b760-42c8-9eb0-8cd461ae7e27.jpg" alt="Image - news sharing" style="width:250px;height:500px;"></td>
  </tr>
   
</table><br><br>



 ### App features : 
 * Views News 
 * Share News 
 * Save News 
 


### MVVM Architecture : 

MVVM is one of the architectural patterns which enhances separation of concerns, it allows separating the user interface logic from the business (or the back-end) logic. Its target (with other MVC patterns goal) is to achieve the following principle "Keeping UI code simple and free of app logic in order to make it easier to manage".

<table align="center" cellpadding="0" cellspacing="0" border="0" width="100%">
<tr><td >
<img style="width:600px;height:400px;" src="https://miro.medium.com/max/875/1*itYWsxQTfq7xTuvIMrVhYg.png" alt="MVVM architecture">
</td></tr>
</table>


#### MVVM components : 

* **Entity:** Annotated class that describes a database table when working with Room.

 * **SQLite database:** On device storage. The Room persistence library creates and maintains this database for you.

 * **DAO:** Data access object. A mapping of SQL queries to functions. When you use a DAO, you call the methods, and Room takes care of the rest.

 * **Room database:** Simplifies database work and serves as an access point to the underlying SQLite database (hides SQLiteOpenHelper). The Room database uses the DAO to issue queries to the SQLite database.

 * **Repository:** Used to manage multiple data sources.

 * **ViewModel:** Acts as a communication center between the Repository (data) and the UI. The UI no longer needs to worry about the origin of the data. ViewModel instances survive Activity/Fragment recreation.

 * **LiveData:** A data holder class that can be observed. Always holds/caches the latest version of data, and notifies its observers when data has changed.
 
 
 ### Navigation Component : 
 
 #### The Navigation component consists of three key parts that are described below:

* **Navigation graph :** An XML resource that contains all navigation-related information in one centralized location. This includes all of the individual content areas within your app, called destinations, as well as the possible paths that a user can take through your app.

* **NavHost :** An empty container that displays destinations from your navigation graph. The Navigation component contains a default NavHost implementation, NavHostFragment, that displays fragment destinations.

* **NavController :** An object that manages app navigation within a NavHost. The NavController orchestrates the swapping of destination content in the NavHost as users move throughout your app.
 
### Retrofit : 
Retrofit is a type-safe REST client for Android, Java and Kotlin developed by Square. The library provides a powerful framework for authenticating and interacting with APIs and sending network requests with OkHttp.

### Application link : <a href="https://drive.google.com/file/d/1hjB8vKHGF_7C7B1QBB0-E7P5eOWmux3t/view?usp=sharing">**Click here to download**</a>

### Future Scope : 

* Add Quiz such as sudoku, words, etc. section in app 
* Display various data, surveys, events( such as earthquake magnitude) in analytical visuals to get better idea.
