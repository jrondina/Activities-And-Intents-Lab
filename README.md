---
title: Activities and Intents Lab - Mad Libs
type: lab
duration: "1:30"
creator:
  name: James Davis
  city: NYC
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Activities and Intents Lab: Mad Libs

In this lab, you will be creating an app based on the game *Mad Libs*.

Mad Libs is a game where you provide certain words and the words are then inserted into a pre-written paragraph with blank spots for fill-ins. Typically, you read the sentence out loud, which usually creates a random (and hopefully, funny) story. [Here's an example of a Mad Lib](http://www.classroomjr.com/wp-content/uploads/2010/05/funny-mad-libs.gif).

This lab will let you practice starting activities and sending data from one activity to another. Also, it will help you practice getting data input from the user, and showing errors when the user doesn't provide data.

## Exercise

#### Requirements

The app consists of two activities.

The main activity should be laid out as follows:

* The layout should have 6 EditTexts, each with hints that describe what type of word is expected.
	* The app should accept the following: 2 adjectives, 2 nouns, animals (plural), and a name of a game.


* The app should have a button that submits the data and starts the Result Activity.

	* If this is pressed and an edittext is not filled out, that edit text must show an error (via [EditText.setError()](http://developer.android.com/reference/android/widget/TextView.html#setError(java.lang.CharSequence)).


* The Result Activity already takes the words you previously entered, and inserts them into the madlibs template of your choice. You have to provide the 6 words, passed as extras to the activity when starting it.

#### Deliverable

An Android app that follows the requirements above. There are no design requirements aside from having the six EditTexts and the button; feel free to play around with color, font, backgrounds, etc.

Post the project on GitHub. Ensure that the project builds and runs successfully.

<img src="screenshots/main_screen.png" height="400px" /> <img src="screenshots/main_screen_with_errors.png" height="400px" /> <img src="screenshots/result_screen.png" height="400px" />


## Additional Resources

* Official Android Developer Website - http://developer.android.com/training/index.html
	* [Building a Simple User Interface](http://developer.android.com/training/basics/firstapp/building-ui.html)
	* [Starting Another Activity](http://developer.android.com/training/basics/firstapp/starting-activity.html)
