Failure is always an option in IT. Probably all running systems have had
some issues. So this is why observability is very important. You have to
know what is going on with your system.


Observability is a very complex topic and there are great books about it.
The easiest concept is that there are 2 types of it:
- "white box" : when you have knowledge about internal details of the system
- "black box" : when you have no idea what is going on inside the system,
you only observe the output


I guess you can compare this to the "problem vs symptom" issue. When you
know and treat the problem ("white box") or the symptom ("black box").


When using a 3rd party library or a SaaS provider in your system, you have
only the "black box" option available. And if you don't have a way to
observe your integrations, sometimes SaaS providers have a feedback loop to
tell you that something is wrong. Like in my daily email pipeline, the
Gmail connector decided that the authorization I gave it is no longer
valid. Good that the Integromat sent me an email about that so I was able
to fix it (re-authorize).


So always check if the SaaS provider you are using has some feedback loop
and if not then implement a "white box" observability in your system.


Paweł
