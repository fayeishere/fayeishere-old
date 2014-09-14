---
layout: post
title: "Internship-Third-Month"
date: 2013-10-31 15:18
comments: true
categories:
---
I signed up for the 3 month internship at the agency in August. If you've read my posts then you know that I spent the first month helping with a protype app but mostly left to my own devices. It's hard to pull in an intern into a busy firm and be able to give them specific work - totally get it. But I wanted to be useful, even though I was having fun learning whatever I wanted and getting paid for it.

Then came month 2. Most was the same until my boss threw me a project. It was Friday, I was out of it, and completely unprepared for an assignment which was due Monday. But I ran. And it was fun combined with stressful. At first I did some research into the terminology that was being thrown around. After I was shown the concept and initial design I began to understand what I was actually suppose to do. Great! A coworker helped me set up my dev environment in order to connect to the server buckets being used (one for development and one for production). And away I went!

I started creating the static page that was the project and got things to look pretty good fairly quickly. It was a pretty simple page. I got to play around with some javascript functionality which made the experience pretty fun. Finally, I felt I was done - but OOPS! - didn't think about mobile etc. Crap. Instead of making it dynamic (with the deadline nearing) I hacked at it and used media queries. And then used more. And then more. Who knew there were so many devices out there? Well - I do now. Annnnd don't forget landscape mode. Phew.

The other part of the project that was thrilling and terrifying was launching it myself. I had help for the first round and learned how to make the following launches on my own. The client wanted to deploy new changes fairly often. Many weekends happened. Success!

And then - just when I thought I was going to be doing independent work again - another project landed! This one was to be website for a donation contest with proceeds going to charity. I was to be the sole developer which was also a bit nervewracking. What the what? So, they wanted a site that displayed 32 players in a bracket system, where the winner of each round played the next. The guidelines were whoever gets the most donations would move on and the final four would compete in an eating contest. All the donations would be going towards OHSU. Pretty cool. The details were that they wanted a current display of a player's donation pool and timers that displayed the current 'heat' countdown as well as the final event countdown. I pulled in IPN from Paypal so that when a donation came in it would update my Redis database and display the results. I was moving and grooving in the dynamic world. Pretty cool.