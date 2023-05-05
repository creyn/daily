Hi there,

There is [[no such thing as the final architecture]].

One thing that strikes me about this ongoing Amazon Prime Video discussion
is that they made the mistake of using serverless to build their system,
because they have now switched to a monolith (is it really a monolith?).

There are few wrong assumptions here. Let me discuss the first one.

First wrong assumption. There is **no such thing as the final
architecture**. Architecture has to change because things change:
requirements, ecosystem, customer base, team skills. To name a few.

Imagine a startup or a unicorn. It has totally different needs than a big
clumsy rhino. **Unicorns need speedboats while rhinos need a cruise ship**.

Serverless architecture has **different purpose** than microservices or
monoliths. Marcin Kolny (the author of the article) admits that: "We
designed our initial solution as a distributed system using serverless
components ... which was a good choice for building the service quickly.".

Serverless architecture is great for that: speed of development and fast
Time To Market.

Please remember, [[change the architecture when architectural drivers
change]].

Don't make your rhino fly.

Change your speedboat to a yacht and then to a cruise ship.

You can read the initial article here:
https://www.primevideotech.com/video-streaming/scaling-up-the-prime-video-audio-video-monitoring-service-and-reducing-costs-by-90

Paweł
