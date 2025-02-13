How to approach System Design?
===


System Design is tricky but it does not have to be difficult- be it a technical discussion at your workplace or your next big interview. Let's talk about how to approach System Design. Something I compiled from 10 years of my career.

## What is System Design?

System Design is all about translating and solving customer needs and business requirements into something tangible. The output system could be an application, a microservice, a library, or even hardware.

There are a couple of approaches that we can use to design any system out there. Picking one over the other depends on the company you work for and the flexibility it provides.

## The Spiral Approach

The Spiral Approach pans like a spiral in which you start with some core that you are comfortable with (database, communication protocol, queue. etc) and build your system around it. Every single component you add to the design is something that you are pretty confident about and can proceed with the added complexities.

For example:

- start with the database
- then add LB and more servers
- then add a queue for async processing
- then other services
- then add synchronous HTTP based communication between them

## The Incremental MVP Approach

In the Incremental MVP-based approach we with a Day 0 design and then see how each component behaves at scale by dry-running it; after identifying the bottlenecks you fix them and re-iterate. You stop the iteration once you are happy with the final product. This kind of approach is typically seen in startups where they do not want to invest in architecture and quickly roll out features.

For example:

- start with Day 0 architecture of users, API servers, and DB
- then you add LB and more API servers
- then you add Read Replica on DB to support more reads
- then you split the service into a couple of microservices
- then you partition the DB to handle more scale

## 3 key pointers while designing systems

- Every system is infinitely buildable, hence fence it well
- Seek clarifications from your seniors
- Ask critical questions that challenge the design decisions

<hr />


<p>Here's the video of me explaining this in-depth 👇‍</p>

[![How to approach System Design?](https://i.ytimg.com/vi/1r9bPisYaOQ/mqdefault.jpg)](https://www.youtube.com/watch?v=1r9bPisYaOQ)

System Design for Experienced Engineers: https://arpitbhayani.me/masterclass
Become a member for exclusive in-depth videos: https://www.youtube.com/c/ArpitBhayani/join
Redis Internals: https://arpitbhayani.me/redis

System Design is tricky but it does not have to be difficult - be it a technical discussion at your workplace or your next big interview. In this video, I share the two approaches that I have been using to design scalable systems in the last 10 years of my career. I will also share the 3 key pointers to remember while designing any system that would help you keep your discussion crisp and focused.

Outline:
00:00 Introduction
02:41 What is System Design?
06:02 The Spiral Approach to System Design
07:27 The Incremental MVP Approach to System Design
09:47 Key Pointers to remember during System Design

You can also
 - Subscribe to the YT Channel [Asli Engineering](https://youtube.com/c/ArpitBhayani)
 - [Download the notes](https://drive.google.com/file/d/185a6688TxLDLXlrDfn2l4ODLSR2m1xLL/view?usp=sharing)
 - Listen to this on the go on [Spotify](https://open.spotify.com/show/7qMoamm2iZQrsPVm6IQLoD)

# Arpit's System Design Masterclass

> A masterclass that helps you become great at designing _scalable_, _fault-tolerant_, and _highly available_ systems.

## The Program

This is a prime and intermediate-level cohort-based course aimed at providing an exclusive and crisp learning experience. The program will cover most of the topics under System Design and Software Architecture including but not limited to - _Architecting Social Networks_, _Building Storage Engines_ and, _Designing High Throughput Systems_.

The program will have a blend of Live Classes happening on Weekends, and 1:1 Mentorship sessions. The program is designed to be intense and crisp to accelerate the overall learning. We tackle every system from the [First Principles](https://en.wikipedia.org/wiki/First_principle) and build the solid foundation to architect any system in the future.


## Highlights

 - The course has been taken up by __500+__ people, spanning __9__ countries.
 - People from companies like Tesla, Amazon, Microsoft, Google, Yelp, Github, Flipkart, Practo, Grab, PayPal, and many more, have taken up this course.


## Hi, I'm Arpit Bhayani 👋

<img width="256px" src="https://edge.arpitbhayani.me/img/arpit.jpg" />

In my last **~10** years of experience, I have worked at **D. E. Shaw**, **Practo**, **Amazon**, and **Unacademy**; and have built systems, services, and platforms that scaled to billions.

Post my masters in CSE from **IIIT Hyderabad** I joined D. E. Shaw for a short stint of 2 months, before moving to Practo and working there as a **Platform Engineer**, building and owning close to 8 different microservices. Post Practo I worked at Amazon on their primary mission-critical E-Commerce Database and built **Data Pipelines** that cold tiered the stale data.

After quitting Amazon in 2018, I joined Unacademy as their first **Technical Architect** and there I designed, built, managed, and scaled services like _Search_, _Notification_, _Logging_, _Deployment Engine_, and many more. I have now transitioned into the role of a Sr. Engineering Manager, leading the Site Reliability vertical.

I also run a YouTube channel [#AsliEngineering](https://www.youtube.com/c/ArpitBhayani) where I post 3 videos every week spanning topics like System Design, Distributed Systems, Microservices, and any interesting CS concept in general.

You can find details about upcoming cohort 👇‍ Hope to see you soon there.

<center>
<a target="_blank" href="https://arpitbhayani.me/masterclass">
<img src="https://user-images.githubusercontent.com/4745789/137859181-d4499cf4-ce65-4466-8b88-a078ece0f081.PNG" width="300px" />
</a>
</center>