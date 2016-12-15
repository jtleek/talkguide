The Leek group guide to giving talks
--------------------

This guide is part of the series of guides that have so far covered [data sharing](https://github.com/jtleek/datasharing), [reviewing papers](https://github.com/jtleek/reviews), and [writing R packages](https://github.com/jtleek/rpackages). The guide is designed primarily for students in statistics and computational biology although some of the ideas will be useful in other disciplines as well.

This guide is a synthesis of some ideas that I got from the following resources:

* Karl Broman's [How to give a scientific presentation](http://www.biostat.wisc.edu/~kbroman/talks/giving_talks.pdf). 
* Zach Holman's guide to talks [speaking.io](http://speaking.io/) and [his actual talks](http://zachholman.com/talks)


Why give talks?
----------------

Uh, cause you got invited?

When you are first starting out you should accept pretty much every opportunity to speak about your research you get. In approximate order of importance, the value of talks early in your career are:

1. To meet people
2. To make people excited about your ideas/software/results
3. To make people understand your ideas/software/results
4. To practice speaking

Later the reasons evolve, altough not be as much as you'd think. The main change is that 4 evolves more into "to show people you are a good speaker". 

The importance of point 1 can't be overstated. The primary reason you are giving talks is for people to get to know you. Being well regarded is absolutely not the goal of academia. However, being well known and well regarded can make a huge range of parts of your job easier. So first and foremost make sure you don't forget to talk to people before, after, and during your talk. 

Point 2 is more important than point 3. As a scientist, it is hard to accept that the primary purpose of a talk is advertising, not science. See for example Hilary Mason's great presentation [Entertain, don't teach](http://www.hilarymason.com/speaking/speaking-entertain-dont-teach/). Here are reasons why entertainment is more important:

* People will legit fall asleep on you if you don't keep them awake - this is embarrassing
* People will never understand your ideas/software/results if they fell asleep and didn't hear about them
* There is __no way__ to convey any reasonably complicated scientific idea completely in an hour
* If you entertain people __they might go read your paper/use your code__ which is the best way to achieve goal 3. 

That being said, be very careful to avoid giving a [TED talk](https://www.ted.com/talks/browse). If you are giving a scientific presentation the goal is to communicate scientific ideas. So while you are entertaining, don't forget why you are entertaining. 


What should you talk about?
----------------

It depends on the event and the goals of the event. Here is a non-comprehensive list:

* __Group meeting__: 
  * __Goal__: Update people on what you are doing and get help.
  * __What to talk about__: Short intro on your problem, brief update on what you've tried, long discussion about where you are going/what you need help on. 
  * __What to bring__: If you are seeking feedback, bring a notepad and pen to keep track of suggestions. You will most likely forget what you don't write down.
* __Short talk at conference__:
  * __Goal__: Entertain people, get people to read your paper/blog or use your software. 
  * __What to talk about__: Short intro on your problem, brief explanation of solution, links to software
* __Formal seminar__: 
  * __Goal__: Entertain people, get people to read your software, make them understand your problem/solution
  * __What to talk about__: Intro to your problem, how you solved it, results, and connection to broader ideas
* __Job talk__: 
  * __Goal__: Get a job, entertain people, make them understand your problem/solution
  * __What to talk about__: Brief overview of who you are, intro to your (single) problem, how you solved it, results, summary of what you have done/plan to do. 


Structure of your talk
-----------

The biggest trap in giving a talk is assuming that other people will follow you because you follow the talk. In general it is always better to assume your audience knows less than you think they do. People like to feel smart. I have rarely heard complaints about people who went too basic in their explanations, but frequently hear complaints about people being lost. That being said, here are some structural tips. Your mileage may vary. 

* __Always lead with a brief, understandable to everyone statement of your problem__. 
* Explain the data and measurement technology before you explain the features you will use
* Explain the features you will use to model data before you explain the model
* When presenting results, make sure you are telling a story. 

The last point is particularly important. Usually by the results section people are getting a little antsy. So a completely disparate set of results with little story behind them is going to drive people bonkers. Make sure you explain up front where the results are going (e.g. "Results will show our method is the fastest/most accurate/best ever"), then make sure that your results are divided into sections by what point they are making and organized just like they would be if you were telling a story. 


Style of your talk
-----------

There are only a few hard and fast rules here. I really like Zach Holman's style guide [speaking.io](http://speaking.io/) and [his actual talks](http://zachholman.com/talks). My suggestion is pick one template/style and go with it for a few consecutive talks to avoid costly overhead. See what you like and what you don't, then edit. Here are the only hard and fast rules. 

* Fonts/colors
  * Title slide must have a contactable form of you (twitter handle, email address, etc.)
  * Fonts can never be too big. Go huge. Small fonts will be met with anger. 
  * Unless you know what you are doing, pick a solid (dark/light) background slide color and an opposite (light/dark) font. 
* Figures
  * Spend time on your figures; they should be clean and *self-explanatory* (although you will explain them)
  * All figures should have big axes in plain English. 
  * Any figure you borrow off the internet should have a web link to the source
  * Any figure you borrow off a paper should have a web link to the paper
  * Pictures beat words by a ratio of 1000 to 1. Pictures on an otherwise word-heavy slide add balance.
* Borrowing
  * Any time you use someone else's slide you should put "Slide courtesy of So and so" with a link to their page

What you should say out loud about figures in your talk
-----------

If you have a figure in your talk you should present it in the following way. 
 
* Explain what the figure is supposed to communicate (e.g. "this figure shows our method has higher accuracy")
* Explain the figure axes (e.g. "the y-axis is sensitivity the x-axis is 1-specificity")
* Explain what trends the audience should look for (e.g. "curves that go straight up at zero and across the top of the plot are best")
 

About equations in your talks
-----------

If you are giving a stats talk you will probably have some equations. That is ok. But the way you present them is critically important to giving an understandable talk. Here are a few important points:

* Before presenting an equation explain the data
* Whenever possible use words instead of symbols in equations (_Expression = Noise + Signal_ is better than _E = N + S_ is better than _Y = X + E_)
* No more than two subscripts
* When explaining an equation
  * First explain the point of the equation (we are trying to model expression as a function of noise and signal)
  * Then explain what each symbol is (E is expression, N is noise, etc.)
  * Then explain how the model relates them (E is a linear function of signal and noise)
* Try to avoid subscripts, and no more than two are allowed. 


Job talk specific issues
-----------

When giving a job talk you have an additional job on top of the four main goals we talked about above. The goal is to present your complete professional persona to a bunch of people who (mostly) won't know who you are. You should tailor this a little bit to the place you are applying to a job, but don't try to pretend to be something you are not. You can show a little more theory at a theory place and a few more results at an applied place, but don't claim you are proving theorems all the time if you aren't. 

You should include both at the beginning and the end of the talk brief summaries of all the stuff you have worked on and plan to work on so they get an idea of who you are in a complete sense. __But only talk about one specific project when giving the talk__. There is nothing more detrimental to your chances of getting a job than going way over time or not getting to give your whole talk. 

Two things that I think you want to convey when giving a job talk are:

1. You would be a fun person to work with and can play well with others
2. You have some unique expertise that will strengthen the place you are applying

Traditionally, people demonstrated #2 by showing that they could prove really hard theorems. At some places, that is still a really good thing to do. Other things that might make you unique are the ability to write amazing R packages that get used, the ability to analyze massive data sets other people can't, the ability to teach courses that students will want to take but the department doesn't have, or ideas about a brand new research area (with some data to back them up). 

Before giving a job talk ask around and get a feel for the sorts of things that people have heard about the place you are applying so you can be smart about your choices of how/what to present. 


Answering hard questions
-----------

Inevitably you will get hard questions during your talk. The most important point is not to panic and not to get defensive. It is way better to just say _I don't know_, then to get upset. When you get asked a really hard question you should:

* Take a second and a deep breath. If necessary, ask the person to repeat the question. 
* Answer the question the best you can come up with on the spot
* Say _I don't know_ if you don't know. If you say I don't know, then you can give your best guess and explain it is a guess. 

The key is to distinguish what kind of response you are giving. Are you giving a response where you know the answer because you actually looked into that? Are you giving a complete guess where you have no idea? Or, what is more likely, are you somewhere in between? 

Most importantly, don't feel embarrassed! Hard questions happen to everyone and if you are polite, explain how sure you are about your answer, and try your best it won't be a problem. 


That one person who keeps going bonkers on you
---------

Almost everywhere you give a talk there will be a person who is upset/intense/aggressive. __Do not fall into the temptation to be aggressive in return__. Answer their first questions politely just like everyone else. If they keep asking really aggressive/lots of questions, you are within your rightst to say: "You are bringing up a lot of good issues, I'd be happy to discuss with you after the presentation more in depth, but in the interest of time I'm going to move on to the next part of my talk". It is ok to keep things moving and to finish on time. 

Finishing on time
----------

Do it. People will love you for it. If you are the last speaker in a session and others have gone long, adapt and go shorter. The value you gain by making your audience happy >>>> the extra 5 minutes of details you could have explained. 


Where you should put your talk
-----------

If you have weblinks in your talk you need to post it online. There is no way people will write down any of the links in your talk. Two good places to put your talks are https://speakerdeck.com/ or http://www.slideshare.net/. But then link to all the talks from one, single, memorable site you can show people at the very end of your talk. All my talks are at http://jtleek.com/talks/. You are welcome to send a pull request with your talk there if it is Leek group related, or you can put them on your own short and sweet web link. 

I personally like Slideshare a little better these days because the slides are much easier to view on mobile phones and iPads, which is the most likely place someone will read your talk. 


Examples
------

Use at your own risk, but these are talks I like or have given (or both :-). 

* [Jeff/Leekgroup talks](http://jtleek.com/talks/)
* [Karl Broman](http://kbroman.org/pages/talks.html)
* [Zach Holmann](http://zachholman.com/talks)
* [Hilary Mason](http://www.hilarymason.com/category/presentations-2/)
* 


Other good/interesting talk guides
---------------

* Nacho Caballero at [F1000Research blog](http://blog.f1000research.com/2014/08/13/how-to-give-a-talk-that-everyone-remembers/)
* Alyssa Frazee on [her blog](http://alyssafrazee.com/ideas-for-super-awesome-conferences.html) 


Contributors
------

* [Jeff Leek](http://jtleek.com/)
