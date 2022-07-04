The Single Responsibility Principle (SRP) is the first of the SOLID
principles that are known to help to write good quality code. There are
many interpretations of the SRP. One of them is: "a class has to have only
1 reason to change". Another one is: "things that change together should
stay together". Yet another is: "a component should do only one thing".

All of those definitions have the same issue that make the SRP the most
mis-understood of all principles. The issue is: "knowledge about the
change". It implies that a developer knows the business domain to the point
that they could group together things that are and will change together and
form one separate element.

And the biggest problem with this "knowledge about the change" is that
there is a gap between the knowledge of business domain experts and
understanding of it by developers. Because of different reasons. But the
bottom line is that a developer does not have the full knowledge about the
business domain that they write the software for.

The problem is known and different techniques have evolved that try to help
to close this gap (like DDD or EventStorming). But they fail over and over,
again for different reasons.

So, should developers stick to the SRP and try to model the business domain
with this limited "knowledge about the change". I would say: NO. Stop
guessing the "single reason to change". Stop guessing which things "change
together". Stop guessing the "one thing". You won't succeed at this.

So what should developers do? Embrace the old good object oriented idea of
high cohesion and low coupling. Pure, technical, code level modeling (based
on the business domain). Admit that you don't know how to do the SRP and
embrace the OOP.

Embrace the change and your possibility to refactor the code (and your
knowledge) in minutes. SOLID was great 30 years ago when we shipped
software on CD-ROMs. Now it is obsolete. And the SRP is misleading.

Because the SRP is for *business domain experts*.
And the OOP is for *developers*.

Pawel
