# Group Project: Begin Wireframes & Software Requirements

## Wireframes

[index.html](http://framebox.org/ApGPN)
[results.html](http://framebox.org/ApGqp)
[about-us.html](http://framebox.org/ApGQb)

## User Stories
Start out by creating at least 5 user stories for your approved project. The outline/requirements for user stories can be found [HERE](https://codefellows.github.io/common_curriculum/projects/UserStories)

Each story in your project management board should contain:

### Story 1

1. Title : CODLE
2. User Story sentence : As a player, I want an educational game that helps me study coding terminology.
3. Feature Tasks : Collection of programming terms to pull from. Array of objects built with a constructor.
4. Acceptance Tests : build a constructor to instantiate objects to pull from.
5. Extra Large

### Story 2

1. Title : CODLE
2. User Story sentence : As a user, I want the game to be aesthetically pleasing so that it is easy to navigate.
3. Feature Tasks : Clean and reactive css design.
4. Acceptance Tests : Site looks good with a nice color pallet.
5. Large

### Story 3

1. Title : CODLE
2. User Story sentence : As a player, I want to see the results from all of my previous sessions.
3. Feature Tasks :  Use local storage to populate a results page with data from previous game sessions.
4. Acceptance Tests : Ensure that the locally stored data persists across page reloads.
5. Mid

### Story 4

1. Title : CODLE
2. User Story sentence : As a player, I don't want to see the same word two round of each other.
3. Feature Tasks :  Use conditional and/or while loops.
4. Acceptance Tests : Ensure that words do not repeat within two rounds.
5. Small

### Story 5

1. Title : CODLE
2. User Story sentence : As a user, I want to know about the development team.
3. Feature Tasks :  Include information about each developer on the about me page.
4. Acceptance Tests : Ensure each developer has information on the page.
5. Mid

## Software Requirements

Using the [Software Requirements Document](https://codefellows.github.io/common_curriculum/projects/SoftwareReqs), create a new file within your main GH repo named requirements.md. Include in this doc the required information for your software reqs for your project as a whole.

## Domain Modeling

Draw out the entities for your project and how they are related to each other. Determine the relationships between the functions/methods and entities of your app.

Include in your domain model the names and data types of your entities and their properties.

Do some research on domain modeling and create your own diagram that represents your app. Here are some helpful resources as a starting point:

1. [Brief introduction to Domain Modeling](https://olegchursin.medium.com/a-brief-introduction-to-domain-modeling-862a30b38353)
2. [Domain Modeling](https://www.scaledagileframework.com/domain-modeling/)
3. [Domain driven architecture diagram](https://medium.com/nick-tune-tech-strategy-blog/domain-driven-architecture-diagrams-139a75acb578)
Include this domain model in the README.md file located in your project’s GitHub repo.

## Using a Database? Make an Database Schema Diagram

If you are using a database of any kind in your project, draft out what your schema will look like by creating a diagram of all your application data models, each in it’s own collection (or table).

Be sure to identify the relationships (if any) between each of your data models:

1. Does a single item in your database “belong to” just one other item in your database? For example, a person has one passport, and a passport belongs to a single person.
2. Does a item in your database “belong to” multiple other items in your database? For example, a house has many residents, and each resident has one primary house.
3. Do many items in your database relate to many other items in your database? For example, a band has many musicians, and a musician can be in many bands.

<br>
Also, include for each seperate collection:

1. The name of each property stored in the collection.
2. The required data type.
3. An indication if this collection is associated with another collection.

<br>
Include this diagram in your readme, accompanied by an explanation of each data model and it’s responsibility in the application.