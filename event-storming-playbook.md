# Event Storming Playbook

## Prep work
1. Remove the chairs!
2. Create the `Key` cards and have then on big posters. Key cards should contain the Postit, the colour and the leading questions with examples. Have a collection of these available as "The Legend"
3. Organise the space - plenty of it. Do not start in the corners!
4. 


## The play
1. Describe the task / activity and the goal we want to achieve to the group. Have the team help create the wall space. Use this picture to guide them. ![img-todo](img.png) 
    1. Show them a completed one for an idea of how it will be built but not in detail, just the colourings. share this blog post [introducing-event-storming](http://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)
    2. Define exploration scope before going into the weeds of it!
    3. 

2. Chaotic Exlporation! Explore the process with Domain Events. Introduce the `EVENT` Postit. The colour, example and the Key should be visible someplace. 
    1. In groups of 2's or 3s if numbers are odd (RH / Cust) have each group identify the `EVENTS` of the system. Timebox this activity as a first pass. 
    2. Once done ask someone to volunteer their events. Spread them on the modeling surface. Timeline does not need to be enforced at this point.  Award the ~ICE BREAKER~ reward
    3. Alternative initialisation - have the faciliator add the first postit as the `pivot event` for others to work from.
    4. There’s no need to add all the events at this point. ES is designed to encourage people to collaborate. You'll find some some of the events will be thrown out during the next steps and new ones added.
    5. Capture scenarios and play through them to see if all the events have been captured.

3. Where are Events coming from (1)? Add the `COMMAND` Postit as well as the `ACTORS`. The colour, example and the Key should be visible someplace. 
    1. In new groups come up with the commands. Timebox activity 
    2. Add the users where they should be

4. Where are Events coming from (2)??
    1. Introduce the `EXTERNAL SYSTEM` if they exist.
    2. Add timed events if needs be (calendar / response to something else)
    3. Cascading reactions -> `POLICIES`

5. Enforce process consistency.
    1. Pick one scenario and model it. 
    2. Model it end-to-end. Replay it backwards
    3. Pick a more complex one -> Repeat.

6. Cluster around state. Introduce the `AGGREGATE`
    1. Look for state machines but postpone naming the things.

7. Shake the system!!
    1. Can the model manage more complex scenarios? Explore these.
    2. Are we happy or sad at the end of the flow - if happy; is someone else sad?


### clarifying questions to ask
* "What circumstances would cause ... to happen?”
* "What was the path that led us here?"
* "What is a good example of ...?"
* "What might lead someone to do/need ...?”
* "What do you mean by ...?" "What else might happen...?