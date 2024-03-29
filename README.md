# TrailersApp
A Demo project for The MovieTrailer based on <b>MVVM clean architecture</b>.

<img src="https://github.com/anitaa1990/TrailersApp/blob/master/media/2.gif" width="200" style="max-width:100%;">   <img src="https://github.com/anitaa1990/TrailersApp/blob/master/media/3.gif" width="200" style="max-width:100%;"></br></br>

#### App Features
* Users can view list of the latest movies of their choice.
* Users can view list of the latest Tv series of their choice.
* Users can filter the movies or tv series based on popularity, upcoming and top rated.
* Users can search for any movie or tv series of their choice.
* Users can click on any movie or tv series to watch the trailers of their choice.


 
 #### The app includes the following main components:

* A local database that servers as a single source of truth for data presented to the user. 
* A web api service.
* A repository that works with the database and the api service, providing a unified data interface.
* A ViewModel that provides data specific for the UI.
* The UI, which shows a visual representation of the data in the ViewModel.
* Unit Test cases for API service, Database, Repository and ViewModel.





#### App Specs
* Minimum SDK 16
* [Java8](https://java.com/en/download/faq/java8.xml) (in master branch) & [Kotlin](https://kotlinlang.org/) (in kotlin_support branch)
* MVVM Architecture
* Android Architecture Components (LiveData, Lifecycle, ViewModel, Room Persistence Library, Navigation Component, ConstraintLayout)
* [RxJava2](https://github.com/ReactiveX/RxJava) for implementing Observable pattern.
* [Dagger 2](https://google.github.io/dagger/) for dependency injection.
* [Retrofit 2](https://square.github.io/retrofit/) for API integration.
* [Gson](https://github.com/google/gson) for serialisation.
* [Okhhtp3](https://github.com/square/okhttp) for implementing interceptor, logging and mocking web server.
* [Mockito](https://site.mockito.org/) for implementing unit test cases
* [Picasso](http://square.github.io/picasso/) for image loading.
* Custom Views: [Loading](https://github.com/yankai-victor/Loading), [Side Menu](https://github.com/Yalantis/Side-Menu.Android)



