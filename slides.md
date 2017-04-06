# EmberConf 2017 Recap

Ben Limmer  
@blimmer

4/11/2017

---

## Ember Community Survey
## Keynote
## Talk by Talk
## Questions from the :peanuts: gallery

***

## Ember Community Survey

```notes
nearly 1600 responses, done every year with emberconf
```

---

## By Version

![](/images/survey/by_version.png)

```notes
many people are using LTS versions, though lots keep up to date with the most current, likely because of glimmer 2.
```

---

## "How can we improve Ember?"

> Performance was a common theme regardless of experience with Ember. Documentation and guide improvement requests were more common from developers with less Ember experience while requests for tree shaking, routable components and mobile support were more prevalent among experienced Ember developers.

---

## "How long have you been working with Ember?"

![](/images/survey/how_long_using_ember.png)

```notes
almost half of survey participants using ember for > 2 years
```

---
## "How many people use your apps?"

![](/images/survey/how_many_people_use.png)

```notes
most target hundreds or thousands of users
```

---
## "What does the server stack look like?"

![](/images/survey/server_lang.png)

---

[View Community Survey](https://emberjs.com/ember-community-survey-2017/)

***
***

## Keynote

A great summary since the last EmberConf and what's next.

---

## Speakers

* [Yehuda Katz](https://twitter.com/wycats) (Ember, RoR, jQuery core teams, yarn, hbs, etc, etc)
* [Tom Dale](https://twitter.com/tomdale) (Ember Core Team)

---

## Main Topics
* Things that went well in 2.x
* Glimmer Deep(ish)-dive
* Things that didn't go well in 2.x
* The future of Ember

---

## What Went Well
* fastboot
* engines
* glimmer

---

## Glimmer

* The third iteration of the rendering engine used by ember
* Now available stand-alone as [glimmer.js](http://glimmerjs.com/)
* glimmer 2 was a **drop-in replacement**

---

## Glimmer Specifics
* No more root attribute (template is the root)
* True es6 class syntax
* Typescript
* es6 getters and setters

---

## Glimmer Performance

* Uses a wire-format to describe DOM operations (slim)
* 'boot up fast and stay fast once booted'

---

![](/images/glimmer/initial_render.png)

---

![](/images/glimmer/update.png)

---

## Future of Glimmer and Ember
* "this is the component API we want for Ember"
* "ember is still the choice for big web applications"
* "glimmer is the choice for small mobile apps that need to be very :racehorse:"

---

## What Did Not Go Well
* communication of...
* `<angle-bracket>` syntax
* routable components
* pods

---

## How to Mitigate in the Future
* Unlock experimentation via a small kernal with hooks
* Early adopters experiment with the addon
* Once things are drop-in compatible, consider merging

---

## Future of Ember

![](images/glimmer/ember_continuum.png)

---

![](/images/glimmer/size_comp.png)

---

## Questions?

:hamster:

***

## Talk by Talk

***

## Going Progressive with Ember

* [Samanta de Barros](https://twitter.com/sami_dbc)
* Engineer at WyeWorks in Uruguay

![](/images/speakers/samanta-de-barros.jpg)
[slides](https://speakerdeck.com/sdebarros/going-progressive-with-ember)

---

## What is a progressive app?
* native-app like functionality from a web app
  * looks good
  * installs on device (fast second boot)
  * works offline
  * is fast

---

## watch this talk if interested in...
* app manifests
* appcache
* service workers
* localforage
* offline web apps

***
***

## A Neurobiologist's Guide to Mind Manipulation
* [Casey Watts](https://twitter.com/kyloma)
* Engineer at Heroku, background in Software & Psychology

![](/images/speakers/casey-watts.jpg)
[slides](https://www.slideshare.net/CaseyWatts/neurobiologists-guide-to-mind-manipulation-08)

---

## Discusses how to...
* improve processing emotions
* improve processing thoughts
* interact more effectively with coworkers

---

![](/images/casey_watts/unhelpful_thinking_styles.png)

---

## watch this talk if interested in...
* something more non-technical
* learning more about "cognitive restructuring"

***
***
## Understanding JavaScript Performance
* [Godfrey Chan](https://twitter.com/chancancode)
* Ruby on Rails and Ember Core Team Member

![](/images/speakers/godfrey-chan.jpg)
[slides](https://speakerdeck.com/chancancode/understanding-javascript-performance)

---

## also `gem install canada`

```
>> [].empty_eh?
=> true
>> [1,2,3].empty_eh?
=> false
>> [].respond_to_eh?(:empty_eh?)
=> true
>> aboot Object.new
=> "#<Object:0x007f802b8b92c0>"
```

---

## Discusses how to...
* debug performance in
  * your code
  * the framework
  * in v8

---

## watch this talk if interested in...
* JavaScript performance debugging techniques
* the performance tab of Chrome dev-tools
* v8 internals

***
***

## Counter-spells and the Art of Keeping Your Application Safe
* [Ingrid Epure](https://twitter.com/ingridepure)
* Full-Stack Engineer at Intercom in Scotland

![](/images/speakers/ingrid-epure.jpeg)
[slides](https://speakerdeck.com/ingride/counter-spells-and-the-art-of-keeping-you-application-safe)

---

## Discusses:
* how to use the browser's content security policy to mitigate xss
* dangers of `htmlSafe`
* using helpers to sanitize html content in user input
* OWASP [Top 10 List](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project)

---

## watch this talk if interested in...
* securing a front-end application
* common attacks on web apps

***
***

## Rebuilding Tumblr as a Single Page App
* [Oli Griffiths](https://twitter.com/Oligriffiths)
* Engineer at Tumblr

![](/images/speakers/oli-griffiths.png)
no slides yet

---

* tumblr is not an ember app
* done as part of a hack-day
* created POC in Ember and React
* testiment to ember's addon-community and ease-of-use

---

## watch this talk if interested in...
* addressing how to rebuild an app with ember

***
***

## Animate the Web with Ember.js
* [Jessica Jordan](https://twitter.com/jjordan_dev)
* Biologist turned Front-End Engineer

![](/images/speakers/jessica-jordan.jpg)
[slides](https://jessica-jordan.github.io/animate-the-web-with-emberjs)

---

## Discusses:
* how to create an animated comic in ember
* keyframe animation
* web animation API

---

## watch this talk if interested in...
* HTML5 Canvas
* web animation API
* comics and drawing

***
***
