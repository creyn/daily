Sometimes I hear the argument that we need to do microservices for customer
experience. As the more traditional monolith approach (a modular monolith)
is seen as slow and clumsy.

But this is not the case. The main reason we have microservices is for
*independent
deployments*.

The monolith vs microservice change should have zero impact on your
customers.

It is not for the ease of scaling. The monolith application can be
scaled up and out as well.
It is not for the ease of development. Quite the opposite. Going from a
monolith to microservices introduces a lot of complexities. Like network
calls, which are extremely slow (yes) and fragile. You have to switch from
a central system to a distributed one. This is a huge minus of
microservices.

But then, you get the huge benefit of being able to have multiple smaller
development teams that are independent. And generally speaking they could
work faster than having all of the developers working on the same monolith
application.

And you could design developer teams in a different way now. Senior
developers could work on the core microservices and junior developers on
supporting or more general services.

So before you decide to go for microservices you should really consider all
the downsides of them. The decision should be a **function of the number of
developers** in your company.

I've created small visual to show that:
https://www.pawelkowalik.com/maps/microservice-architecture-is-for-developers/

Paweł
