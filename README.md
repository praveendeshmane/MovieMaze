## MovieMaze

Your one-way stop to browse and search the next movie you are going to watch.
Browse among an infinite list of the most popular movies or search your whatever matches your mood.
Add to favorites, see details like cast, director and more. Check it out now!

## Screenshots

<img src="https://github.com/Charis1331/MovieMaze/blob/main/screenshots/s1.png" width="300"> <img src="https://github.com/Charis1331/MovieMaze/blob/main/screenshots/s2.png" width="300"> <img src="https://github.com/Charis1331/MovieMaze/blob/main/screenshots/s3.png" width="300"> <img src="https://github.com/Charis1331/MovieMaze/blob/main/screenshots/s4.png" width="300"> <img src="https://github.com/Charis1331/MovieMaze/blob/main/screenshots/s5.png" width="300">

## Tech Stack

* Minimum SDK version 26
* [Kotlin](https://kotlinlang.org/) based, [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) & [Flow](https://kotlinlang.org/docs/reference/coroutines/flow.html) for asynchronous operations and multiple data streams filtering [(MutableStateFlow)](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/-mutable-state-flow/).
* [Koin](https://github.com/InsertKoinIO/koin) for DI.
* Jetpack
    * [Paging3](https://developer.android.com/jetpack/androidx/releases/paging) - take advantage of TMDB API's paging capabilities
    * [Room](https://developer.android.com/jetpack/androidx/releases/room) - pair it with paging for offline support
    * [Lifecycle](https://developer.android.com/jetpack/androidx/releases/lifecycle) - persist core data during configuration changes
* [Retrofit](https://github.com/square/retrofit) - for all the API requests
* [Glide](https://github.com/bumptech/glide) - for image loading
* [MDC](https://github.com/material-components/material-components-android) - use of shared element transitions
* [Gson](https://github.com/google/gson) - for parsing JSON data
* [Truth](https://truth.dev/) - assertion library for Tests
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver) - to test the endpoint validity of each request
* [Barista](https://github.com/AdevintaSpain/Barista) - a wrapper around Espresso, to make UI testing easier

## MAD Score

![Summary] (/mad_scorecard/summary.png)
![Kotlin] (/mad_scorecard/kotlin.png)

# License
```xml
   Copyright 2020 Charis1331 (Charalampos Choulis)

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```