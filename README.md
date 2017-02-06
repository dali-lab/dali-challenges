# DALI Developer Challenges

![](docs/imgs/dali-mondays.gif)

For new applicants to the DALI Lab we ask developers to do a challenge.  DALI hires two levels of developers based on experience and motivation.  You may apply for dev I or II by completing one of the following challenges below.

These challenges allow you try your hand at some design and some web coding as well as the ins and outs of an essential concept used in software design and development — version control. We'll be using git and github (the site you're at now!) to learn how manage multiple people working on the same document at the same time — all while having the ability to backup and revert your work. If this is all new to you, don't worry! We'll start from the beginning and build from there.

If you get stuck, don't be discouraged! If you have any questions, we encourage you to email us at applications@dali.dartmouth.edu or stop by Sudikoff 007 during DALI Open Lab Hours (every Monday 6-9pm).

## DALI Level I Challenge

DALI members are pretty cool, so we'd like each of you to design a web page telling us about yourself! Build your page using html/css/js (follow details in [Dev Details](#detailed-instructions)). Be creative and adventurous! If you are really passionate about writing, add some blog posts, if you really enjoy photography, integrate your 500px portfolio, and maybe you love to travel, include a cool map visualizing all of the places you have visited. Your design should tell us something about your personality, so consider this when you make choices about the design, layout, and various components of your website.

### Your page should include the following information:
* A picture of yourself
* Your name
* Where you’re from or where you live
* A short bio telling us about yourself (you might include/mention: design/programming applications you know/like, what you enjoy most about UI/US design/development, why you’re excited to work with DALI.)
* Something interesting/fun/random about yourself :smile:

### Inspiration

Below are some examples of awesome pages that DALI Lab members have created that you could base your personal pages on.

* [Kathy Dong](http://kathydong.com/)
* [Jenny Seong](http://jennyseong.me/)
* [Luisa Vasquez](luisavasquez.me)
* [Tim Tregubov](http://www.zingweb.com/)
* [Annie Ke](http://annieke.me/)
* [Lillian Zhao](http://www.zhaolillian.com/)
* [Danah Han](http://danahhan.me/)
* [John Kotz](http://cs.dartmouth.edu/~jkotz)
* [Pat Xu](http://www.patrickxu.com)
* [Jason Feng](http://www.jasonfeng.com)

### Detailed Instructions

[Dev I Details](./docs/dev_I_details.md)

Make sure you don't miss the [questions](#questions) below!

## DALI Level II Challenge

This challenge is a bit more independent than the Level I challenge. If you are familiar with the tools and techniques in the Level I challenge then this one is for you!

Developer II's are expected to have a strong foundation in Git and should be comfortable using terminal. They also have experience in at least one web or mobile technology and should be comfortable learning and working independently.

## Overview

At DALI, we have over 50 students per term working on a variety of cool projects.  Things can get pretty chaotic.  It would help if we had an app or a site that displayed a DALI Dashboard!   This dashboard could show active and past members,  profiles,  skillsets,  and current projects for DALI Members. It could show some visualizations of where members come from and what they are working on. Additionally it could have project information and potentially show a record of the processes as well.  

Here is some data to use [in JSON format](http://mappy.dali.dartmouth.edu/members.json)

```
{
  "name": "NAME",
  "iconUrl": "//mappy.dali.dartmouth.edu/images/foo.jpg",
  "url": "//somedomain.com/",
  "message": "harrrooo",
  "lat_long": [4.444676,-75.242438],
  "project": ["a cool project", "more cool project"]
}
```

### Dev II Details

Build an app or website using a technology of your choice.  Keep in mind that many DALI projects are iOS/ReactNative or web.  You should parse the JSON data http://mappy.dali.dartmouth.edu/members.json in your app and display at least some of it.

Your deliverables:
* Functional app/website
* Parse and display JSON data in some format using HTTP GET
* Features required:
  * display real data
  * display photos
  * filter or toggle to change data displayed
* GitHub repository showing git work flow (commits) while coding

Some cool web technologies to look at:
* Frontend Framework - [React](https://facebook.github.io/react)
* Chart Library - [Chart.js](https://github.com/chartjs/Chart.js)
* Mapping Library - [Leaflet](https://github.com/Leaflet/Leaflet)
* Color Manipulation - [Chroma.js](https://github.com/gka/chroma.js)
* Data explorer - [Recline](http://okfnlabs.org/recline/)
* WebGL Based Map Visualizations - [Deck.gl](https://github.com/uber/deck.gl)

## Questions?

- **q.** Should I do Dev I or II?!
- **a.** If you have had significant experience building software projects from scratch such as webapps or mobile apps you should definitely attempt Dev II.

- **q.** How are Dev I and II evaluated?
- **a.** Dev I and Dev II applications will be evaluated separately.


If you have any questions, we encourage you to email us at **applications@dali.dartmouth.edu** or stop by **Sudikoff 007** during DALI Open Lab Hours (every Monday 6-9pm).

## Submitting Your Challenges

In the email that you received there should be a customized link for you to submit your samples.
