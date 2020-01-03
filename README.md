# Smogler #

Location based air quality information, on your iPhone and your Apple Watch. Swift 5, iOS 11-13, and watchOS 4-6 compatible.

## How do I get started? ##

The first step is to [acquire your own token for the WAQI API access](https://aqicn.org/data-platform/token/#/).

Look up the `token` constant in `APIService.swift` and replace the dummy string with your token.

The project has no external dependencies at the moment, so you should be fine building/running it. :+1:

### Where's the air quality data coming from? ###

From the [public API](https://aqicn.org/api/) of the [World Air Quality Index Project](https://waqi.info/) originating EPA.

## How does the app look like? ##

1. iPhone app

![Smogler iPhone](https://user-images.githubusercontent.com/1460573/48306624-c8fb5a80-e4f0-11e8-9e0a-11fa91fd0837.png)

2. Watch app

![Smogler Watch](https://user-images.githubusercontent.com/1460573/48306633-fd6f1680-e4f0-11e8-8b15-c46bdd9b646f.png)

3. Watch complication

![Smogler Watch complication](https://user-images.githubusercontent.com/1460573/48306634-fd6f1680-e4f0-11e8-84b4-e76b47fda181.png)

## What's next?

There's always room for improvement, Smogler is no exception. 

[1.](https://github.com/vasarhelyia/Smogler/issues/4) Make sure things fetch the API only when necessary and try to move all the load possible to the iOS app. That was the initial goal, but there are so many scenarios (iOS app active, background, etc., Watch app active, background, ...), I might have gotten a bit lost sorting these out.

[2.](https://github.com/vasarhelyia/Smogler/issues/5) Writing tests for the Watch extension is not trivial, but it would be nice to see how it's possible.

[3.](https://github.com/vasarhelyia/Smogler/issues/1) Push notifications - to be alerted in case the air quality dropped, for example.

[4.](https://github.com/vasarhelyia/Smogler/issues/6) More supported complication families?
