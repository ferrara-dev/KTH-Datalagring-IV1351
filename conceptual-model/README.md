# Task 1 - Conceptual model
## Intro
The first task of the project course is to create a conceptual model for the Soundgood music school database.
- The conceptual model must cover the entire description of the Soundgood music school company given in the project description. 
- The diagram must be made either in UML or in one of all possible crow foot notations (for example IE notation). 
- Use inheritance in at least one place in the conceptual model.


## Method
This chapter explains the procedure followed to create the conceptual model.
Step 1: noun identification
Step 2: category list
Step 3: remove unnecessary entities
Step 4: find attributes
Step 5: find relations
Third
step was to make the attributes in the entities which was done by following three rules; an
attribute could only be a string, boolean, number, date or time, an attribute can’t have other
attributes and an attribute can’t be in another entity. 
. The fourth step was to make the relations between each entity. This
was done by thinking, what corresponds together and why. Thereafter was a name added to
each relation, the name should explain the relationship between the ententies. Directly after,
was the cardinality of the relationships defined this was done by reasoning with myself what
The Soundgood music school database is modeled using UML notations using the online modeling software lucidchart (ref here)

### Step 1 - Idenfiying entries
We want to collect and analyze the data requirements given in the project description, so the first thing we need to do is to 
actually identify as many possible entries as possible.

To find possible entries we want to list everything in the project description that can be identified as a thing or object in the real world with an independent existence.
This is done in a couple of steps:
1. create entity for every noun in the description  (if not redundant).
2. create entities from functional viewpoint (category list, payments, rentals etc) (if not redunant)
3. filtered to remove redundant or unecessary enties.
4. review (repeat)

### Step 2 - Identifying attributes
Each entity is descriped by its particular attributes
The rule below was implemented to identify attributes for our resulting canditates : 
1. An attribute can only be a string, boolean, number, date or time,
3. an attribute can’t have other attributes and an attribute can’t be in another entity.

When this was done, all canditates that did not have any attributes were filtered out.

### Step 3 - Indentify relations
In the third and final step in the process of creating our model, we are looking to identify relations and cardinality between the entities we have found.


## Result
This chapter will show and briefly explain the resulting conceptual model.

## Discussion

### Are there attributes for all data that shall be stored? Is cardinality specified for all attributes?

### Are all relevant relations specified? Do all relations have cardinality at both ends and name at least at one end?

### Are all business rules and constraints that are not visible in the diagram explained in plain text?
