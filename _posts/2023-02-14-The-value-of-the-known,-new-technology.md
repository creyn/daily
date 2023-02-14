An interesting friction between developers and architects when it comes to
choosing a technology. A new technology especially.

Imagine you are a developer that comes to a new company and to a new team.
The team and the company uses one type of database: SQL Server. A
relational database engine. This is the way they are doing things.

Now, you get a task to implement some feature that would benefit from using
a document database like MongoDb. You know that because you've used it in
your previous job. So you are proposing this to the team as a perfect tool
to do the job. There is this saying "using the right tool to do the job".
And MongoDb is the tool for that feature. The team might agree with you as
they also like to learn new technology and find MongoDb as a perfect
solution for your task.

And this is where the friction is. Because this situation is a nightmare
for architects. As architects have to look at that from a more broad
perspective. From the point of view of the entire company. It is not that
architects don't know that this is the right tool for the job. The problem
is that it is a new tool (at least in that company).

Architects have to worry about all those **Non Functional Requirements**
(NFRs). Like:
- reliability
- availability
- performance
- scalability
- security

Plus: what is the support level for this technology and what licenses we
have to pay.

The most important part is as always: money. We don't have skills in our
company to: develop (what would happen if that one developer is on
vacation?), test, deploy, rollback, maintain, upgrade, etc. There are a lot
of things to learn (which takes time) or buy (like hire new QAs and DevOps
people).

So I always tell my developer colleagues to look at everything they do from
a broad, company-wide perspective. And I tell my architect colleagues to
allow developers to use and learn new tools. But carefully.

Paweł
