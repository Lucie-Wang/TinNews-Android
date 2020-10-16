# TinNews-Android

<strong>💼 Overview </strong>: This is an Android mobile project inspired by the Tinder's Swipeable feature but for news, written in Java. 
<p>The application has three main components: 
<ul>
<li>Home fragment shows all the latest news obtained from newsapi.org, the user can swipe right to save the news for a later read, swipe left to discard the news. 
It can also be achieved by using the thumb up and thumb down buttons instead of swiping gestures. </li>
<li>Search fragment allows the user to search for news by typing in the keyword.</li>
<li>Save fragment displays all the news that the user has liked/swiped right/thumbed up, he/she can also click on the news image tiles to read the details or click on the heart icon to unlike/unsave the news</li>
</ul>
</p>

<div align="center">
  
![TinNews App Demo ](./tinnews_demo.gif)

</div>

<strong> ⚒ My Work at a Glance</strong>
<ul>
  <li>Designed the News app based on Google Component Architectural MVVM Pattern</li>
  <li>Implemented the bottom bar & page navigation using JetPack navigation component</li>
  <li>Utilized 3rd party CardStackView(RecyclerView) to support swipe gestures for liking/disliking the news</li>
  <li>Built the Room Database with LiveData & ViewModel to support local cache and offline model</li>
  <li>Integrated Retrofit and LiveData to pull the latest news data from a RESTFUL endpoint (newsapi.org)</li>
</ul>

**✍ Author: Lucie Wang** - [https://github.com/Lucie-Wang](https://github.com/Lucie-Wang)
