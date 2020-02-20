# Project 2 - *SimpleTweet*

**SimpleTweet** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **X** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can **compose and post a new tweet**
  - [X] User can click a “Compose” icon in the Action Bar on the top right
  - [X] User can then enter a new tweet and post this to twitter
  - [X] User is taken back to home timeline with **new tweet visible** in timeline
  - [X] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  - [X] User can **see a counter with total number of characters left for tweet** on compose tweet page

The following **optional** features are implemented:

- [ ] User is using **"Twitter branded" colors and styles**
- [ ] User can **click a link within a tweet body** on tweet details view. The click will launch the web browser with relevant page opened.
- [ ] User can **select "reply" from detail view to respond to a tweet**
  - [ ] User that wrote the original tweet is **automatically "@" replied in compose**
- [ ] User can move the "Compose" action to a FloatingActionButton instead of on the AppBar.
- [ ] Compose tweet functionality is build using modal overlay
- [ ] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [ ] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [ ] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be **persisted to disk** and can later be resumed from the compose view.
- [ ] User can enable app to **receive implicit intents** from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet.

The following **bonus** features are implemented:

- [ ] User can tap a tweet to **open a detailed tweet view**
  - [ ] User can **take favorite (and unfavorite) or reweet** actions on a tweet
- [ ] Use the popular ButterKnife annotation library to reduce view boilerplate.
- [ ] On the Twitter timeline, leverage the [CoordinatorLayout](http://guides.codepath.org/android/Handling-Scrolls-with-CoordinatorLayout#responding-to-scroll-events) to apply scrolling behavior that [hides / shows the toolbar](http://guides.codepath.org/android/Using-the-App-ToolBar#reacting-to-scroll).

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="walkthrough4.gif" width=250><br>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
    
    
# Project 2 - *SimpleTweet Part 1*

**SimpleTweet** is an android app that allows a user to view his Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can **sign in to Twitter** using OAuth login
- [X]	User can **view tweets from their home timeline**
  - [X] User is displayed the username, name, and body for each tweet
  - [X] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [X] User can refresh tweets timeline by pulling down to refresh

The following **optional** features are implemented:

- [ ] User can view more tweets as they scroll with infinite pagination
- [ ] User can tap a tweet to display a "detailed" view of that tweet
- [ ] User can open the twitter app offline and see last loaded tweets
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.
- [ ] Replace all icon drawables and other static image assets with [vector drawables](http://guides.codepath.org/android/Drawables#vector-drawables) where appropriate.
- [ ] User can see embedded image media within the tweet detail view
- [ ] User sees an **indeterminate progress indicator** when any background or network task is happening
- [ ] User can **see embedded image media within a tweet** on list or detail view.
- [ ] User can **click a link within a tweet body** on tweet details view. The click will launch the web browser with relevant page opened.
- [ ] User can view following / followers list through any profile they view.
- [ ] User is using **"Twitter branded" colors and styles**

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="walkthrough.gif" width=250><br>
<img src="walkthrough2.gif" width=250><br>
<img src="walkthrough3.gif" width=250><br>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
