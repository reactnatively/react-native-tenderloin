# React Natively

Projects that use React Native to tell the story of humanity. Here we'll capture how humans interact with each other using technology.

## Tenderloin

We're creating a simple app to allow iOS &amp; Android users the ability to swipe through different quotes and tell us if they have heard it before.
* Users would swipe left if they've never heard of the quote ~~dish~~.
* Users would swipe right if they have heard of the quote ~~dish~~.
* Seperately, users may also choose to add a comment.

The quotes ~~dishes~~ display would be provided via API. Each swipe would then POST data to the API provided.

_PLEASE NOTE: It is important that this app be developed with React Native because we want to deploy to our student group for testing on either iOS or Android devices._

|User Action|View|Priority|
|-|-|-|
|User register|<img src="https://github.com/reactnatively/react-tenderloin/blob/master/tenderloin-register.png" width="150">|Medium|
|User login|<img src="https://github.com/reactnatively/react-tenderloin/blob/master/tenderloin-login.png" width="150">|Medium|
|Quote displayed|<img src="https://github.com/reactnatively/react-tenderloin/blob/master/tenderloin-home-quotedisplayed.png" width="150">|Critical|
|Quote displayed with comments|<img src="https://github.com/reactnatively/react-tenderloin/blob/master/tenderloin-home-quotedisplayed-withcomments.png" width="150">|Critical|

## React Natively API
* URL: http://api.reactnatively.venny.co/v1/
* endpoint: /quotes

|Key|Value (Example)|Description|
|-|-|-|
|token|NWU1MWQ4NzIwOTY0OGNjMTNkZWI1MjNiMjA1ZA==|Token required for access to the API|
|text|If you are not willing to risk the usual you will have to settle for the ordinary.|Quote  (1111 Characters|
|lines|<SVG>|Any SVG paths (1111 Characters)|
|image|directory/subdirectory/image.file|Image file associated with the quote (255 Characters)|
|audio|directory/subdirectory/audio.file|Audio file originated with the quote (255 Characters)|
|longitude|32.7820148|Longitude of user when post occurs|
|latitude|-96.8003555|Latitude of user when post occurs|
|altitude|150|Altitude of user when post occurs|
|author|83838383|User ID of the user authoring object|
|audience|33333333|User ID of the user who is audience to this object|
