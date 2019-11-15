---
layout: post
title: Let's Get Started!
subtitle: For What Purpose?
tags: [inspirational]
---

I have often considered starting a technical blog over the years.  Previously, I always found reasons to NOT start 
(work... kids... life), but today I am finally doing it!  In hopes of inspiring others into action, I thought 
I would start with discussing two topics.  The first is "Why now?", and the second is "What has influenced me?"

##Why now?
The first is why now? For what purpose am I putting myself out there?  In short, I recently co-presented a topic
on how Spring Boot Autoconfigured libraries can be used to codify organizational standards and best practices 
at the 2019 SpringOne Conference ([#ShamelessPlug](https://www.youtube.com/watch?v=iWQxTHoSsgY&list=FLAEhr0qP8JZOZaX3ko6Ve-w)). 
It was a lot of work to get prepared and feel confident that I wasn't going to stumble all over my words, and in
the end I am pretty proud of how it turned out.  The real kicker was that we had a pretty good size group show up.
They asked questions and were really engaged.  The fact that there were several people that stayed around to ask
questions (for 20 to 25 minutes, until we got kicked out for the next session) and share their experiences spoke to me.

It was clear that there were developers trying to tackle the same challenges we were, and that any insights
we could share on how we had been successful was of value to them.  I walked away from it with the feeling 
that we may have opened some eyes to the possibilities of what could be done, and gave them some tools to start 
down the path.  I had the feeling that we may have planted a seed in 2 or 3 organizations... or 
maybe 6 or 8... or maybe more!  The idea that we may have helped other organizations struggling with the same 
challenges was very rewarding.

I would challenge everyone to find something you are passionate about, technical or otherwise, and find a means
of sharing what you've learned.  There will be others that are just as passionate or have the desire to learn
and grow.  It will be work, maybe hard work, but it will be rewarding!

##What has influenced me?
If I were to sum up my personal brand (in software development) in one word, it would be "quality".  I can't really tell you whether my
focus on quality has driven me toward these influences or is a result of them.  Its rare that my code 
makes it into a PR, much less Production, without simplicity, readability, and a comprehensive set of tests.  If it does, possibly due to outside
pressures, that situation won't last long.  I take pride in my code, and I want it to serve as an example to
whomever may lay eyes on it in the future.  As a result, I am a fan of [Test Driven Development (TDD)](https://en.wikipedia.org/wiki/Test-driven_development).  
I am by no means an expert, but I do recognize the mindset shift it brings and I look for regular opportunities 
to apply it.

The largest influence on my approach to design/development has to go to the [Spring Framework](https://spring.io/projects/spring-framework).
The concepts of [Inversion of Control and Dependency Injection](https://www.baeldung.com/inversion-control-and-dependency-injection-in-spring) 
have dramatically affected how I construct classes.  It produced a shift from building complex functionality through
subclassing to using composition.  Even in the early days of Spring with XML configuration files, the classes that
resulted were clean and simple. Declare what the class needs in a constructor (yes, I prefer constructor-based 
injection), and voila! One stateless, singleton instance ready for use anywhere you want to use it.  And let's not 
forget the nice little side effect of it producing a class that is super easy to write unit tests for.

I would describe the years that followed as evolutionary, rather than revolutionary.  Once again it was the team 
around Spring that brought the next aha! moment... even if it didn't seem like it at first.  

I was introduced to Spring Boot a few years ago.  When I first looked at it, my initial thoughts were basically 
"Okay, its a container to run my application (beans) in and its a little lighter weight than a JEE
container and its opinionated... but will I like their opinions".  Whether you agree with their opinions (I usually do)
or not, the real power lies in the autoconfiguration mechanism that delivers those opinions.  It is wide open
and available for anyone to develop their own opinions.  Teams, organizations, enterprises, and vendors are all
able to build opinionated libraries that autoconfigure Spring Boot applications with the standards and best 
practices that make the most sense for their developers or customers.  Its shifted my thinking on framework 
libraries from considering class design to bean design.  Developers no longer have to look up how to get started
using a library and how to instantiate appropriate instances.  In many cases, they simply need to **add the library
to their project and that's it!** Interested in learning more? Watch for a future post on the subject...

Next up is "Uncle" Bob Martin and a presentation of his that I came across, ["Uncle" Bob Martin - "The Future of Programming"](https://www.youtube.com/watch?v=ecIWPzGEbFc&list=FLAEhr0qP8JZOZaX3ko6Ve-w).
The video references possible government regulation of software development.  I really have no idea how likely that
is, nor is it the part I am referencing here.  The piece that caught my attention was the idea of software development
being treated as a profession and the principles that should be expected from said profession. Have you ever thought about
the core principles that should govern development? Look for a future post on the subject to see my views.

The last piece of the puzzle regarding code influencers is pride.  I have spent a lot of time reviewing other
people's code... and from time to time... wondering why they felt their code was ready for others to see.  There
are a lot of things that can evoke this question:
1. System.out
2. //TODO implement error handling
3. Classes, fields/methods that aren't used
4. Class/field/method names that don't represent the usage/behavior... at all
5. No tests

I am sure this is a little judgy, but as technical leader, I feel compelled to walk the walk.  If I don't set a good example and push to have
pride in my own work, how can I expect others to do the same?  Are you proud of your last pull request?  I hope
you are.  

**If not, then go do something about it!**

