# Midori/Bird
Project for Junction Tokyo 2019 AI Track

## Inspiration
Going from A to B is not as simple as it sounds, with some many options people tend to select the fastest route. Individuals often do not acknowledge pollution, fitness levels or the effect of the outdoors on their mental wellbeing. Along with the fact that 40 % Japanese adults are physically inactive and similar trends across the rest of world. This is attributed to long working hours, growing attachment and addiction to mobile devices. But what if we can encourage and promote healthier routes via gamification and big data.
## What it does
Integrated into your own mapping applications, is a new pathfinding algorithm that takes your physical, mental as well as the environmental health into consideration as you move around and interact with the world around you.
Implementing technology from [API’s], our system maps out walking routes that avoid environmental hazards, and guide users along routes that cater to their individual preferences, instead of just moving along the shortest/fastest route.
Retention and adoption of the technology is encouraged by gamification aspects.
By walking along certain types of routes users can unlock different kinds of virtual bird avatars, and in order to keep the “health” of these birds up, users are encouraged to walk along routes that fit the characteristics of these birds. 
For instance: if the user walks along a route that avoids staircases, the flightless penguin becomes healthier and happier.

## How we built it
We used a combination of open-source tools to build Midori/Bird. We used OpenStreetMap data to generate our map model in QGis. Based on heuristic data, we reweighted the vertices of the graph using advanced statistical methods. The resulting graph was then exported such that we could run our python search algorithm on it. 

## Challenges we ran into
We noticed that even though APIs are listed, they might not work.

## Accomplishments that we're proud of
Using QGis in a hackathon :)

## What we learned
QGis, python

## What's next for Midori/Bird
