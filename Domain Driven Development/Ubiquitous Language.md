#DDD #SoftwareDevelopment

# Usage
Ubiqutious Language is a [[Strategic Design]] pattern when [[Domain Expert]], engineers and other workers use defined somewhere business terms to discuss about project. All participants of development processes should contribute to ubiquitous language.

# Rules
Ubiqutious Language must be:
* Ambiguousity-free each term of [[Subdomain]] must be used for one thing. 
* Contain only business terms, no technical jargon like *tables*, *abstract factories* and so on, because ubiquitous language's goal is make communication between engineers and domain experts easy.
* Clear: all terms for everyone should be described in understand and simple way.

# Tools
## Glossary
Glossary is good for describing structural and characterizing terms like users, roles, processes and so on. But glossary is hard to use for describing the behaviour of entities. So it would be a good idea to use glossary with other tools like use cases.
## Use cases
Use cases describes the behaviour and processes in system. Author's talking about Gherkin as about an example of such tool. Gherkin tests allows domain experts verify that all business-logic have valid expected behaviour.