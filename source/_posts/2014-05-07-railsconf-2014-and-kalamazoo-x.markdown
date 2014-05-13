---
layout: post
title: "RailsConf 2014 and Kalamazoo X"
date: 2014-05-07 16:33:12 -0500
comments: true
categories: [RailsConf 2014, Kalamzoo X]
---

##RailsConf 2014

I was lucky enough to volunteer for RailsConf 2014. It was an amazing experience, and I learned quite a bit from the talks I was able to attend.

###[Keither and Mario's Guide to Continuous Deployment with Rails](http://www.railsconf.com/program#prop_410)
This was an interesting look at managing an automatic deployment configuration with multiple testing stages. It truly is amazing what you can do with a continuous integration suite, tied into an automatic push to master, supplemented with smoke tests.

Additionally, it's the only tech talk I've witnessed that involved a spontaneously combusting wallet.

###[Demystifying Data Science: A Live Tutorial](http://www.railsconf.com/program#prop_164)
It was really interesting to watch Todd live code some scraping and data analytics. He made it seem extremely simple to generate interesting visualizations of word frequency on wedding records. He also mentioned [Rap Stats](rapgenius.com/rapstats) - an amusing look at the frequency of words in rap tracks.

###[Debugger Driven Development with Pry](http://www.railsconf.com/program#prop_376)
This blew my mind. I've used pry and pry-nav to debug and sort through the stack before, but using rescue on your rails server and even rspec was something that was really cool. It was extremely cool to see Joel work through making specs pass without running them twice. This did lead to some mirth on my part after seeing 4 specs pass in 9 minutes, several seconds.

Pry is an exceptional tool with extensions that fully realize the power of digging through the stack and making changes on the fly - no reload required.

###[Effectively Testing Services](http://www.railsconf.com/program#prop_433)
Gone are the days of blowing API calls to test a feature. Gone are the days of being unable to work without internet connectivity. This was a great talk on how to properly test API services - specifically how to stub out the responses while still making them properly testable.

###[Software Development Lessons from the Apollo Program](http://www.railsconf.com/program#prop_82)
Unfortunately, I couldn't stay for the whole talk, as I was working a shift during the latter half. That said, I loved relating computing to the space program. I've always been enamored with human space flight.

Learning more about the roots of the computing revolution was fantastic. Female developers should take pride in knowing that the basis of computer science relied upon work that 'Computers' (the job title) did during the foundation of the microprocessor era. Many women were instrumental in this process.

###[An Ode to 17 Databases in 33 minutes](http://www.railsconf.com/program#prop_228)
I quite enjoyed the DnD style character card representation of databases. Toby gave us a tour de force look at a wide variety of databases. There are plenty of options, and the choice of which one to use can be difficult. I've earmarked RiakDB, Neo4j, Hyperdex, and ElasticSearch for further research.

###[Bring Fun Back to JS: Step-by-Step Refactoring Toward Ember](http://www.railsconf.com/program#prop_266)
Ember is a flavor of javascript that I'm looking forward to delving into. I've heard several of the rants against javascript, but it is incredible how flexible it is. Making the front end more cohesive is certainly something that I'm yearning for.

###[The "Rails of JavaScript" won't be a Framework](http://www.railsconf.com/program#prop_220)
Lineman.js is an exciting development. What Rails does for ease of creation of a web app, Lineman extends with and easy setup of javascript. I love how simple Rails makes generating a web application, but the javascript side can have teething pains. Utilizing Lineman seems to eliminate some of the headache by providing standardization in application.

I'm excited to try it out when I can manage to find time for it. There are so many exciting languages, frameworks, and testing utilities that I feel like I'll never have enough time to explore them all properly.

###Tenderlove's Keynote
Aaron's keynote was hilarious and exciting. His arguments that science has a place in web development struck true with me. It isn't the low level stuff, but science provides some metrics for improvement.

He demonstrated this with his fork of ActiveRecord, AdequateRecord. He ripped out some of the more ubscure querying methods and inconsistent behavior. After this, he set about adding some cacheing to speed up querying. The improvements were astounding to say the least. Querying through 17 has_many :through relations took a similar amount of time as compared to a single table query. This will help eliminate some of the more grotesque cacheing implementations and extraneous relations that I've used in the past.

As an extra bonus, I got to shake Aaron's hand and claim my very own Gorbypuff sticker!


##Kalamazoo X

Right after closing down the information booth at RailsConf 2014, I jumped in a car and headed off to Kalamazoo, MI for Kalamzoo X. This conference focused more on soft skills and leading a productive life without facing burnout.

My favorite [session](http://kalamazoox.org/2014-2/sessions/) was Leon's Allegory of the Cave by Leon Gersing. As we are increasingly immersed in technology, we adopt the ideologies of the companies and communities we follow. Instead of holding the values of the community around us, which may involve conflicting ideals, we isolate ourselves into a cave of 'yes men' who all share the same ideals and become increasingly extreme upon them. To see this in action, look no further than the 'Great Smartphone Wars' we are wading through today. There is incessant bickering between the fanboy camps about who is the best - and not only who is the best, but that everything else is rubbish. We associate the technology with the person in these virtual communities and become exceptionally closed to any other viewpoints. We group into small passionate communities with no voice of dissention or reason - We become 'us' and 'them'. They are the enemy, and we are the good guys.

This is important. People need to free themselves from the singular viewpoint and be open to others. Collaboration is key, and eventually, no matter how sheltered you are, you must work with someone you disagree with. If you are so mired in your 'us vs. them' viewpoint, and extrapolate your choices, you won't be able to properly work together, let alone see merit in an opposing viewpoint.
