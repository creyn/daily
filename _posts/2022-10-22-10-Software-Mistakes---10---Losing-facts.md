> You could build any report if you don't lose the facts

# Problem
When government regulations have to be implemented, there are always new
tables in the Data Warehouse required. And new processes to feed those
tables. It takes additional time to implement.

# Solution
Just use **Event Sourcing** and store all the facts.

# Benefit
You can **replace audit logs** and application state with a projection from
all the facts. This way **any new report is a no-brainer**, just another
projection.

Paweł
