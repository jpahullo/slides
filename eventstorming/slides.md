# Event Storming

*Jordi Pujol Ahulló* | [@jpahullo](http://twitter.com/jpahullo) | Working at [URV - SREd](http://www.sre.urv.cat)

![Tarragona Developers Meetup](images/meetup_tarragona_developers.png)

[@tgndevs](http://twitter.com/tgndevs) | [Meetup](https://www.meetup.com/Tarragona-Developers-Meetup) 

----

# Why
# Event Storming?

----

# Product Requirements

---

Assume you have to build a new software

<img src="images/newproduct.jpg" title="Building a new product" width="70%"/>

---

How do you collect the requirements?

<a href="https://pxhere.com/en/photo/510878">
  <img src="images/collecting.jpg" title="Collecting requirements" width="70%"/>
</a>


---

How long it takes? Weeks? Months?

<a href="https://pxhere.com/en/photo/1060726">
  <img src="images/time.jpg" title="How long it takes?" width="100%"/>
</a>

---

What if #?&ÑqwY%$"@ ?


<a href="https://pxhere.com/en/photo/201300">
  <img src="images/whatifs.jpg" title="How ifs?" width="80%"/>
</a>

---

Surrounding a table?

<a href="https://pxhere.com/en/photo/727881">
  <img src="images/surroundingtable.jpg" title="Surrouding a table?" width="80%"/>
</a>

---

Dealing with personal positions?

<a href="https://pxhere.com/en/photo/810626">
  <img src="images/personalpositions.jpg" title="Dealing wiht personal positions?" width="80%"/>
</a>

----

# Key question

---

Collecting and building a set of requirements<br>
is a **learning process**?

<a href="https://www.maxpixel.net/Pen-Write-Articles-Child-Learning-Process-Drawing-1570634">
  <img src="images/child_learning.jpg" title="Learning process" width="50%"/>
</a>

---

"Children learn as they play.<br>
Most importantly, in play children<br>
learn how to learn."<br><br>
<a href="http://parentingthegods.com/o-fred-donaldson-original-play-ultimate-grace/" target="_blank">O. Fred Donaldson</a>

---

# "Let's Play!"

<a href="https://www.maxpixel.net/Win-Success-Happy-Children-Play-Video-Game-593313">
  <img src="images/children_playing.jpg" title="Let's play!" width="70%"/>
</a> 

---

## Set the requirements
# in hours 
## instead of months

----

## Let's do
# event storming

----

## Personal Disclaimer

* I'm a newbie
* I'll do my best


<a href="https://media2.giphy.com/media/5S2WLYMVMHTna/giphy.gif">
  <img src="images/michaeljordan.gif" title="Michael Jordan.. ok!" width="40%"/>
</a>

----

## The beginnings

1. Alberto Brandolini <a href="https://twitter.com/ziobrando">@ziobrando</a>
1. <a href="http://ziobrando.blogspot.com.es/search/label/EventStorming">Event Storming appeared as such on 2013</a>
1. Book on leanpub: <a href="http://eventstorming.com/">EventStorming</a>
1. Coaching on <a href="https://www.avanscoperta.it/en/">Avanscoperta</a>
1. Before: event-driven modeling

----

## Content Disclaimer

* Information here is from public domain
* Some focus or approach here is particular to our own experience
* Focus of this job: introductory but ready to apply (please!)
* Images from public domain are linked to the site.

----

# Are you ready?

----

# Methodology

---

## Change in mindset

---

## Focus on events and business process
### ~~not in data~~

---

## Based on stickers

* Tactile 
* For taking decisions
* Fast and cheap

<a href="https://github.com/mariuszgil/awesome-eventstorming/raw/master/assets/timelapses/timelapse-1.gif">
  <img src="images/timelapse-1.gif" title="Event Storming Timelapse" width="80%"/>
</a>

---

## Participants are key

* Ubiquitous language
* Focus on Core Domain
* They WILL learn
* Quick reaction to
    * Misunderstandings
    * Doubts
    * Problems

---

## Versatile

* Big picture
* Design-level modeling

---

## Timing

* 2-3 hour sessions
* Sleep & Relax
* Repeat first step

---

## Translatable

... into DDD

... to source code

----

# Ingredients

---

Room: with big wall and paper roll


<a href="https://www.maxpixel.net/Indoors-Window-Fair-Weather-Architecture-Empty-3065345">
  <img src="images/empty_office.jpg" title="Empty office" width="80%"/>
</a>

---

Stickers of different colours

<a href="https://www.maxpixel.net/Sticky-Notes-Messages-Office-Contact-Notes-2566916">
  <img src="images/stickers.jpg" title="Stickers" width="80%"/>
</a>

---

Markers, one for each participant

<a href="https://www.maxpixel.net/Business-The-Hand-Pen-Hand-To-Write-Marker-427516">
  <img src="images/marker.png" title="Markers" width="80%"/>
</a>

---

_**Key people**_: Domain experts & Developers & ...

<a href="https://www.maxpixel.net/As-Children-Enjoy-River-Splash-Water-The-Bath-1822704">
  <img src="images/key_people.jpg" title="Key people" width="80%"/>
</a>


---

Facilitator: referee + coach role

<a href="https://pxhere.com/en/photo/1088875">
  <img src="images/coach.jpg" title="Facilitator" width="80%"/>
</a>


----

# Steps for event storming

---

## Preparing things and people

1. Prepare the room (preferably empty room)
1. Put the paper roll fixed on the wall: 20-30 minutes
1. Give a pen to every participant: 5-10 minutes
1. Introduce the "game rules": 15-25 minutes

---

Let's play!

<a href="https://www.maxpixel.net/Girl-Celebration-Funny-Painted-Happy-Colorful-438139">
  <img src="images/lets_play.jpg" title="Let's play" width="80%"/>
</a>

----

## Introduce
# simple,
# game rules

---

Stickers and colours

<a href="https://github.com/mariuszgil/awesome-eventstorming/raw/master/assets/timelapses/timelapse-1.gif">
  <img src="images/timelapse-1.gif" title="Event Storming Timelapse" width="80%"/>
</a>

---

* orange: domain events; in past participle tense
* light blue: commands; before domain events; imperative tense

<a href="https://en.wikipedia.org/wiki/Event_storming#/media/File:Event_Storming_actor.jpg">
  <img src="images/Event_Storming_actor.jpg" title="Sticker and colours" width="50%"/>
</a>

---

But there are more colours ;-)

* purple/red: problem; describe it
* lilac: Process to execute after an event
* pink: External systems / Bounded context name
* green: user view (drawings)
* pale yellow: entity/aggregate; a noun

---

Working in rounds (pomodoro style)

<a href="https://www.maxpixel.net/Time-Items-Black-Clock-Roman-Numerals-Things-2589161">
  <img src="images/pomodoro.jpg" title="Pomodoro" width="80%"/>
</a>

---

Prevent* long-term discussions

<a href="https://www.maxpixel.net/Communication-Bleat-Communicate-Discuss-Talk-Sheep-2372148">
  <img src="images/long_term_discussion.jpg" title="Pomodoro" width="80%"/>
</a>

----

# Phases

Generic recommendation path

Based on <a href="https://www.pearson.com/us/higher-education/program/Vernon-Domain-Driven-Design-Distilled/PGM332632.html" target="_blank">Domain-Driven Design Distilled, Chapter 7: Acceleration and Management Tools, Vaughn Vernon</a>

---

## Divide and conquer

First conquer, then divide

---

## Flood with domain events

* Paper roll = "infinite" timeline
* From left to right = precedence
* Vertical placement = parallelism

---

## Commands and Processes

* **Commands** causes the existing events
* **Processes** to run due to:
   * an event exists
   * a command was run

* A **process** starts other(s) **commands** 

Generic timeline: Command / Event / Process

---

## Which aggregates?

On top of every pair Command / Event

place the pale yellow sticky note with the

Aggregate (or Entity) 

---

## Boundaries

Outline the boundaries + pink sticky note

<a href="http://verraes.net/img/posts/2014-07-23-event-storming-fake-domains-happy-paths/event-storming-wall.jpg">
  <img src="images/event-storming-wall.jpg" title="Event Storming wall with boundaries" width="80%"/>
</a>

---

## Define views and roles

Draw in green sticky notes the **views**. The information necessary
for the user to take a decision.

Draw in small sticky notes the **role** of the user running a **command**.

---

## Results

The force side



---

The dark side of the force

<a href="https://cdnx.livechatinc.com/developers/uploads/2017/04/event-storming-session-1-e1491921794656-700x525.jpg">
  <img src="images/event-storming-session-1-expectations.jpg" title="Event Storming wall with boundaries" width="60%"/>
</a>

----

# As a participant

Let's keep ... !

* Open-minded
* Focused
* Analytical
* Deliberative
* Proactive

---

# As a participant

You will learn! 100% sure!

----

# As a facilitator

* Hard worker

---

# The facilitator

* Who? Anyone (What? *)
    * Self-learned (make retrospective meetings)
    * Taught on facilitating event storming
* Expert on the domain? 
    * Not necessary to know anything about the context

---

## Facilitator tasks (1/3)

Make the learning process work

First conquer, then divide

---

## Facilitator tasks (2/3)

Manage time!

25 minutes for play
5 minutes for retrospective

---

## Facilitator tasks (3/3)

Make participants keeping ...!

* Focused
* Analytical
* Deliberative
* Proactive

----

## Tips for facilitators

---

When discussions appear among participants:

* Let them time for a while, consider productivity
* No more than 5-10 minutes a group discussing
* A blocking discussion? 
   * Stop it!
   * Delegate a proposal on a participant
   * Propose divide the problem being discussed
* Knowledge-building discussion?
   * It's OK!

---

Look at body language. Promote active attitude.

* Motivate opening new kind of events
* Motivate diving into a part of the problem
* Make them think about events time line
* Sitting down is not a problem. Changing viewpoint?

Keep ALL participants in play

---

Make questions

Do not give solutions

---

Implicit knowledge have to be **explicit**

---

Focus on the core of the problem 

(your domain on DDD)

---


Build an ubiquitous language (DDD)


----

# Relationships with...


**DDD**: Domain-Driven Desing

**CQRS / ES**: Command Query Responsibility Segregation/Event Sourcing


----

# More resources

* http://ziobrando.blogspot.com.es/2013/11/introducing-event-storming.html
* https://github.com/mariuszgil/awesome-eventstorming
* https://techbeacon.com/introduction-event-storming-easy-way-achieve-domain-driven-design

---

* http://verraes.net/2014/07/event-storming-fake-domains-happy-paths/
* http://verraes.net/2013/08/facilitating-event-storming/
* http://verraes.net/2015/03/event-storming-storytelling-visualisations/

---

* http://sch3lp.github.io/2014/07/12/event-storming-exercise/
* https://developer.procurios.com/post/2016/08/25/Three-event-storming-workshops-a-report
* http://tpierrain.blogspot.com.es/2015/08/event-storming-domain-distillation.html?m=1
* https://es.slideshare.net/mobile/jeppec/event-storming-48594742
* https://blog.redelastic.com/corporate-arts-crafts-modelling-reactive-systems-with-event-storming-73c6236f5dd7

----

# Conclusion

1. Collecting requirements
1. Traditional way vs innovative event storming
1. Event storming rules
1. Participant: How to attend to a session
1. Facilitator: How to manage a session

----

# Thanks!

Special thanks to **SREd**

*Jordi Pujol Ahulló* | [@jpahullo](http://twitter.com/jpahullo) | Working at [URV - SREd](http://www.sre.urv.cat)

http://jpahullo.github.io/slides/eventstorming/
