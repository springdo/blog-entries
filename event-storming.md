# Event Storming

## Notes from the Brandolini Workshop

#### What is it?
Modelling technique that allows you see the forest, the wood and the trees. Provide an unlimited modelling space.
It is a pattern for exploration and discovery. Software creation is an exploratory task, while exploring more learning occurs. Direct learning about a business leads to blindspots.

#### Big Picutre ES
Comes in two types:
1. For business and where they are _now_
2. For where they'd like to go

#### Why do we do it?
1. We use ES to identify the _right_ problem vs the problem we _think_ exists.
2. To make trouble. ES is like opening Pandoras' box, we want people talking about it and talking about the difficult bits of our business.
   
#### The Legend
* **System** - in Big Picture ES. Is there something that can affect our probability of success? Is it a Software? Is it a diff Company? Is it a group or org that could influence things? It could even be something external; eg the weather!
* **People / Actor** - Who is the actor? The user? Best practice is to be fuzzy about the definition of _who_ to keep people in the loop 
* **Read Model** - I have a decision. What information do i need to make that decision.
* **Policies / Proceedures** - Whenever. Keyword is whenever. Eg _whenever_ a ticket is purchased, a welcome email is sent. These act as the glue between the bounded context. Further exploration of these will drive inconsistencies in the aggregate. 
* **The Aggregate** - The state machine of a concept in our model. Often it needs to be opened and closed. The aggregate will receive the command and produce one or more events. Top tip: try not to name it until the very end! 

#### Facilitation Tips
* Don't be the first to put a sticky on the wall! But give the Ice Breaker award to the person who does.
* Timing for the ES; Watch from the line of the wall to see when people are starting to come back away from it. Use this to guide your timing. As people pull away, ideas might be running out, energy could be low or perhaps the leading questions need to be re-worded.
* Temptation is to park the hard conversations with Pink Postits. Hide these until they’re really needed.
* Be fuzzy about detail until it is needed.
* In Big Picture ES; your job is to hunt out the inconsistencies in the story. As you move from Events > Systems > People; make sure you capture pain points. Body language can be key to identifying this
* Separate the roles in the ES (Facilitator to people). As a facilitator your job is to be ignorant; you can ask the silly question others are afraid to ask. 
* Facilitator is Mr. Stupid. Create a safe env for people who don't know their business well enough but are too afraid to ask the questions.
* Step back from the wall (and landscape) when explaining and reviewing the flow. Be part of the converstation. If you're _walking the wall_ people will see you as part of the problem and not drive the conversation they need to have with each other.
* Explicit Walkthrough. As Mr. Stupid move through the flow telling the story exactly as you see it. People will correct you (as Mr. Stupid) but possibly not each other
* During the explicit walkthrough rotate to diamond shape if things are not written accurately or need to be more explored. Explore the story from the boundry events as there may be more to uncover.
* If time is short; run through the story with a bullshit buzzer for people to call out when to stop.
* Reverse the narative to discover additional events. Starting at the end will id corner cases and a less optimistic story. Edges and failure paths not initially identified will surface
* Look for timed events; these are often negative events.
* If the flow branches, keep a main one on top with branches flowing down
* Record a video of the ES so it can be replayed by the group. Share this with others.
* Use `Arrow` voting. Two per person. Reason for this is with two votes each, people will vote once for their thoughts and once for the groups. Sneaky tip, give IT guys green arrow stickes and business blue. See where the distribution of the pain is and lead this to force further conversation.
* Don't do the ES in a corner (or start it there either!). Corners cause people to bump into each other and break the flow. People miss out on key information and contribute less.
* Invite the right people - selection bias will affect the outcome that people vote for
* How do you stop yourself recreating your problems? Watch out for the Dungeon Master.... 
  1. Diverstify the people in the room
  2. Keep your events at a business level
* Think you've got the whole flow mapped out? Then identify Happy / Sads. or Value Gotten / Missing. Uncovering these in the flow will identify more new ground unexplored. Eg Purchase complete = happy for customer but cost time etc for back end fullfilment. 
* Hold off making decisions until you've modelled enough. Eg seat / reservation. A reservation may not contain a seat but you'll only know by further modelling the system.


#### Sorting the Wall (Big Picture Flavour ES)
* Bubble sort is very inefficient. It’s the default behaviour for us all to use but is actually the most difficult to complete. Suggested Alternatives
    - Create _phases_ in the process. Eg Checkout flow to group to gether events and sort based on that.
    - Add Pivotal Events. Try to define these by business value.
    - Swim lanes. Con with this method is you'll run out of space quickly.
    - Temporal Milestones. Very rigid but also very useful for timed activities. Eg you have to Eventstorm planning RWC2019
    - Combi of Phases & Pivotal Events
 