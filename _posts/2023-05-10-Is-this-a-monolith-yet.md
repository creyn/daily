Hi there,

Currently a lot of developers and architects cheer for the monolith and are
against serverless (or microservices). Plus, now they use the Amazon Prime
Video case to prove their point. That even the Amazon people cannot make a
serverless app profitable and switched to a monolith.

The problem is that they didn't switch to a monolith. They used the wrong
name.

As we know, in IT the most difficult thing is to **name things properly**.
Another one is: **how big a microservice is**. I would add another one:
**is it a monolith yet**?

I think that Marcin Kolny writing the article mistaken a "properly-sized"
microservice with a monolith. And now everybody else is copy-pasting this
mistake.

Let me emphasise this. "Amazon Prime Video monitoring service" is currently
a microservice, not a monolith.

So what is a microservice and how is it different from a monolith?

A microservice is a service that is responsible for running one
functionality. But what is this one functionality? It might be anything.
Really. Depends on the team. And the team should decide if we need one
application or many applications.

I hope you know that **microservices are for developers not customers**,
and are used when you have too many teams for a single application. So they
don't get in each other's way. **Microservices are for independent
deployments** and not for scalability (as they pointed out in the article,
they could scale this new single application in a similar way they did with
serverless).

A monolith on the other hand, is an application that has multiple
functionalities and responsibilities. Simple as that.

Another golden rule in IT is: **we can solve any problem by introducing an
extra level of indirection**.

We know that having good abstractions is very difficult. Imagine a single
responsibility for the kids: organise your toys. The application for that
would be a microservice right? Another one: put your dirty clothes in the
laundry basket. Another microservice right? But for the parents it is a
wrong abstraction level. Because for the parents the single responsibility
will be: clean your room. So **is it a monolith yet**? Or a "better-sized"
microservice?

And what is the responsibility of the "Amazon Prime Video monitoring
service"? It is: monitoring video streams for quality issues. It doesn't
even handle the fixing process. So is this new single process a monolith?
Or just a "properly-sized" microservice?

I argue that it is the "properly-sized" microservice. It is too small to
call it a monolith.

You can read the initial article here:
https://www.primevideotech.com/video-streaming/scaling-up-the-prime-video-audio-video-monitoring-service-and-reducing-costs-by-90

Paweł
