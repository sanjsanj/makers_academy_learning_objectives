# BDD

### Define BDD
BDD is Behaviour Driven Design, allowing developers, management and stakeholders to define software specs.
Its creator Dan North defines it as follows:
> BDD is a second-generation, outside-in, pull-based, multiple-stakeholder, multiple-scale, high-automation, agile methodology. It describes a cycle of interactions with well-defined outputs, resulting in the delivery of working, tested software that matters.

### Explain how BDD works
In BDD you write a wide, over-arching feature test that describes a desired behaviour or interaction as infered from user stories, watch it fail, write the requisite smaller unit tests to provide coverage for your feature test, watch them fail, write the application code to make your tests pass then rinse and repeat from the beginning.

### Explain how BDD and TDD are related
BDD is a continued development or evolution of TDD.  It provides a framework for deciding how and where to begin your testing, employing user stories and domain modelling.

# Domain Modeling

### Define 'Domain' as the abstract area in which the problem is defined (0) [Samm's brief introduction (reading), Scaled Agile Framework: Domain Modelling (reading)]
### Define 'class structure' (0) [Samm's brief introduction]
Recall that a Domain Model describes key concepts in the domain and the relationships between them (0)
Explain that defining the problem in plain English is a good first step to a Domain Model (0)
Explain how to extract a Domain Model by analysing the nouns and verbs in a plain English description of the problem (0)
Illustrate links between User Stories, Domain Models, and Class Structures
RSpec

Know what RSpec is (0)
Know to use _spec in filenames if they include tests (3)
Explain that RSpec provides a natural, English-like syntax (1)
Explain how RSpec is a DSL (1)
Explain why RSpec's syntax is helpful for developers (1)
Fail an RSpec test (1)
Debug code to pass an RSpec test (1)
Use describe, it, and expectation syntax (2)
Use respond_to syntax (2)
Use RSpec implicitly-defined subject syntax (2)
Use RSpec 'predicate' syntax
Use RSpec 'context' syntax
Select the lightest useful testing method (2)
Assess when is appropriate to use RSpec's one-liner syntax (3)
Analyse why sometimes tests pass when it seems like they shouldn't (3)
Evaluate the difference between RSpec failures and Ruby errors (3)
Refactor tests (3)
Doubles

Define doubles as a kind of 'stunt stand-in' for objects in testing (2)
Explain that doubles are useful to avoid interacting with 3rd-party services (2)
TDD

Know what an 'acceptance' (or 'feature') test is (intro)
Know what an 'integration' test is (1)
Know what a 'unit' test is (intro)
Explain that starting with tests helps us to avoid going mad (1)
Organise a spec-driven filesystem (1)
Set up a unit test (3)
Link RSpec failures to progress in TDD (2)
Assess which properties to implement into objects using TDD as a guide (3)
Move between unit and feature tests (3)
Analyse why code should be written in a TDD manner (3)
Analyse why passing tests does not guarantee fully-working code (3)
Debugging

Define a 'stack trace' (3)
Explain how to use a stack trace to debug errors (3)
Debug errors using a stack trace (3)
OOP

Define OOP (intro)
Explain that OOP allows us to write more flexible code (intro)
Explain why modular code is useful for future code maintainers (intro)
Agile

Define an 'Agile' process (intro) [Wikipedia (reading), Agile Manifesto Principles (reading)]
Explain how to apply Agile methodology to development (intro) [Scrum Reference Card (reading, visual)]
Differentiate between BDUF, NDUF, and EDUF [Samm's brief introduction]
Work in an Agile way (0 onwards)
Link Agile methodology and TDD (1 onwards)
Evaluate why Agile methodology is so popular
Pair Programming

Define 'pair programming', 'driver', and 'navigator' (intro)
Explain why pair programming is so useful in development (intro)
Use pair programming techniques (0 onwards)
Argue for why pair programming is often better for code quality than solo programming
Evaluate how pair programming with a new partner every day has developed their proficiency in other topics, and more generally
Style Guides

Give an example of a style guide (intro)
Recall that it is better to write self-explanatory code than fill code with comments (1)
Install and run RuboCop (1)
Analyse why 'linters' like RuboCop are useful when developing (1)
Correct style violations (1)
User Stories

Recall the structure of a user story (intro) [Wikipedia (reading), Agile Modelling: User Stories Introduction (reading)]
Elicit user stories from clients (intro)
Select high-value user stories (1)
Interfaces

Define an interface as a way to interact with a system (1)
Recognize that IRB is an interface (1)
Setting up a project

Recall how to set up a simple project (0)
Explain why a complete README is important (0)
Initialize and push a git project (0)
MVP

Define an MVP as a Minimum Viable Product (1)
Explain that an MVP is the minimum set of operating features for a client to test a business model (1)
Ruby

Know to include files in other files using require (2)
Outline Ruby convention for require (2)
require a file in another (2)
Differentiate between require and require_relative (3)
require_relative one file into another (3)
