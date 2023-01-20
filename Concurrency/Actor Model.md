#Actors #Concurrency 
# Actor
Actor is an agent which plays its role when message occurs.
## Intention
Intention is a contract for actor with outside world, it is how we communicate with it and what we expect from him.
## Extendibility
Actors can create others actors for different tasks. For example, web-server got a bunch of requests and create actors that step-by-step process them.
## Protection
Actors can be used within others actors only if they have compatible contracts.
## Structuredness
Programms with actors have no goto's and other hard to understand control flow, they have straightforward communication via messages.

# Usage
Alan Key has used Actor Model to implement [[Object-Oriented Programming]] in [[Smalltalk]]