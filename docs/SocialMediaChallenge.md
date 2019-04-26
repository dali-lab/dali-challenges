# 🤳 DALI Social Media Challenges

There are two challenges you can consider. One is frontend while the other is backend. You can choose between the two or even both!

![](https://media.giphy.com/media/PEss2FFDJgTks/giphy.gif) ![](https://media1.giphy.com/media/81qzW2HFlIPDO/giphy.gif?cid=790b76115ca7adc96263346d6bda4bd6)

## Frontend Challenge 🎨

If you're passionate about coding frontend layouts, and would like to code a ~snazzy~ social media front-end, read on!

### Overview

Chances are, you've interacted with a social media app like Snapchat, Instagram, or Facebook at some point. What all of these apps have in common is that they have simple, but sleek, user-friendly UIs. A not so known fact is that you don't have to be a designer to put a UI like that together! Through harnessing the power of libraries/packages and native UI components, you'll be able to go from zero to 🦄-social media hero.

[Insert images of social media here]

Here at DALI, we have over 70 members and we'd like a way to display these members in a social media-like format.

### Objective

The objective of this challenge is to take a given dataset of DALI member information and create a social-media-like UI to display all of the information from our members with some additional functionality. 

Don't worry! This isn't the backend challenge so we'll be providing you with a static [JSON file](../data/Dali_Data.json) to load into your project, and then all you have to do is create the UI to display it. If you want to use a data storage service like [Firebase](https://firebase.google.com) for the data storage go ahead, but the JSON file should be enough to get you going!

#### Things to keep in mind
* You will want your social media platform to display user profiles 👥**and at least two other features**.
* Feature possibilities are endless, but some things that could be added are post creation, following/friending users, likes/reactions, notifications and/or anything else that you think would be cool!
* The social media platform doesn't need to be publicly hosted or available but we should be able to download and run your project from GitHub using either `npm` or `yarn` for web apps or something like Android Studio or Xcode for mobile apps.

### Instructions 📋 

1. Choose a platform. React.js is a common choice for full-stack web development and Swift and React-Native are popular choices for moible development, but feel free to choose another coding language!
2. Break down the UI into key views---a Profile view and Posts view, for example---and work from there to add the detailed sub-components.
3. Many languages/IDEs have pre-built components like TextFields or TableViews that you can use in the creation of your app; however, here are some packages that you can use in the creation of your social media platform:

    #### React.js + React-Native
    * [React Bootstrap](https://react-bootstrap.github.io/) (only React): the magic of bootstrap, but for React!
    * [Redux](https://brainhub.eu/blog/react-libraries/): a state manager for React that makes data handling easier
    * [React-Modal](https://github.com/reactjs/react-modal) (only React): an easy way to present modal alerts in your web app
    * [Axois](https://github.com/axios/axios): simplifies the handling of network requests
    * [Formik](https://github.com/jaredpalmer/formik): easy form handling and validation
    * [React-Router](https://github.com/jaredpalmer/formik)(only React): allows the setting up of multiple urls from your base url
    
    
    #### Swift
    * [EmptyDataSet-Swift](https://github.com/Xiaoye220/EmptyDataSet-Swift): a nice display for when a list or table has no data
    * [SCLAlertView](https://github.com/vikmeup/SCLAlertView-Swift): upgrade to native alert views
    * [Hero](https://github.com/HeroTransitions/Hero): nice animations and transitions
    * [JJFloatingActionButton](https://github.com/jjochen/JJFloatingActionButton): an action button with different animation options
    * [SDWebImage](https://github.com/SDWebImage/SDWebImage): an easy way to load and cache images via url in your app
    * [SwiftIcons](https://github.com/ranesr/SwiftIcons): pre-loaded icons from FontAwesome, LinearIcons etc.
    * [PushNotifications](https://cocoapods.org/pods/PushNotifications): easy to use PushNotifications using [Pusher Beams](https://pusher.com/beams)

    These are by no means the only libraries and packages out there!

4. While this challenge is not geared specifically towards designers, we do expect your frontend to look nice, so be creative and have fun! 👩‍🎨👨‍🎨

## Backend Challenge 🛰️

This challenge allows your backend skills to really shine!✨

### Overview

As we get more members in the lab, the more personalities that we meet! It would be helpful to have a webserver that could hold DALI member related information and provide endpoints and functions for developers to interact with data.

### Objective

Create a webserver or API that allows other developers to access and interact with the data. This is fairly broad so you have the most freedom to interpret this challenge. There are few things that you should keep in mind when you are working through this challenge:

1. Create a REST API with at least GET/POST routes
2. Add extra functionality beyond just sending back data to the requester
3. This API doesn't need to be publicly hosted, but we want to have it run locally on our machines with either [`npm`](https://www.npmjs.com/) or [`yarn`](https://yarnpkg.com/en/)

This challenge is language-agnostic! So feel free to use Javascript, Python, Java, or whatever feels most comfortable to you.

### Instructions 📋 

We've collected data on lab members so you don't have to!

There are two version of data in JSON files that you can use:

1. [Public data](https://github.com/dali-lab/dali-challenges/blob/master/data/DALI_Data.json) - each chunk has a lab member's name with unique information
2. [Anonymous data](https://github.com/dali-lab/dali-challenges/blob/master/data/DALI_Data-Anon.json) - each chunk doesn't have a name attached with some different data

Here are some things to think about:

1. Imagine that this API needs to be used for a data visualization project. What type of endpoints would you create to make it for front end developers?
2. How would you connect fairly similar types of chunks to one another?
3. Try to get creative by incorporating both data sets into your API.

### Tips
To make the development process easy, consider reading through this list

1. Use [VSCode](https://code.visualstudio.com) for a better development environment
2. `yarn` is a slightly faster node package manager
3. Consider using the following frameworks
    * [`Express`](https://expressjs.com/) for Javascript
    * [`Flask`](http://flask.pocoo.org/) for Python
4. Draw inspiration from Twitter, Facebook, Instagram, Reddit, etc.

The more creative you get with this challenge, the better! If you have any questions feel free to email the [DALI Lab](mailto:staff@dali.dartmouth.edu). Good luck 🚀
