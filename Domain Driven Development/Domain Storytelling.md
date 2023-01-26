#DDD #StrategicDesign #SoftwareDevelopment

# Domain Storytelling
A modeling tool which visualize the business process via pictures, symbols, and graph flow.

# Boundary contexts indicators
* One-way information flow
* Difference in language
* Different triggers: time vs on demand

# Example
For example, we have a restaurant, and a client orders a pizza by phone; for phone operator this order is nothing but a list of requirements, so we can vizualise that with a 📋 symbol. Then phone operator gives this order to a cook, and a cook think about this order as a what they need to cook, so we can visualize this with a 🫕 symbol. After long process of cooking, the order comes to delivery driver, they think about this order as a package to deliver, so it's a 📦 symbol. Also there is a delivery navigation system that scans city traffic everyday, because it's expensive to build a route 'on demand'.

Here we can see a difference in language, because we use different symbols for the same thing, and this is how we find [bounded contexts](Bounded%20Context.md). Also, the information flow: order never returns back to a phone operator or even a cook, because an order moves through boundary contexts; this reminds me of [pivotal events in Event Storming](Event%20Storming.md#Pivotal-events). And we can see another boundary context, a delivery navigation system, because its trigger first of all is time, not a demand like in cooking, or delivery contexts.
![Simple Restaurant Domain Story](./Assets/Simple%20Restaurant%20Domain%20Story.png)

# When
This is a good option when:
* You want to show how people work together
* Your [domain experts](Domain%20Expert.md) primarily are non-tech people
* You want to analyze stages of the business process

# Further reading
1. [Find Context Boundaries with Domain Storytelling](../Library.md#^find-context-boundaries-with-domain-storytelling)