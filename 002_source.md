---
layout: default
title: The Source
number: 002
---

# The Source

Model District Post Office

{% assign media = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.media_type == 'image'" %} 

{% include media.html pages=media %} 

<br>


## Key

**Bottom Left:** 
In this view from above, the Post-Yard is shown as a square courtyard, its main building (bottom center, grey cube) facing out to the road, flanked by gates.  

Along the edges of the courtyard, you have (proceeding clockwise from bottom left):
- A Gatekeeper's Room
- A Granary
- A Storage Room for Harness
- A Barn
- The Stables
- A Barn
- A Storage Room for Harness
- A Root Cellar
- A Room for Postillions (*pochtal'iony*).[^1]

The center of the plan reads: "A sample arrangement for a post-yard, where space allows."

**Top Left**:
This area provides a key to the first and second floor drawings (to the right) of the main post office.

**First Floor**

- a: Front entryway with a small counter (marked NB) for accepting mail.  
- b: The mail office.  
- c. A room for travelers and mail carriers (*pochtarei*).  
- d. Staircase up.  
- e. Rear entryway.  
- f. Kitchen.  
- g. Servants' quarters.  
  
**Second Floor**

1. Main staircase.
2. Rooms for travelers.
3. Common room.
4. The postmaster's quarters.
5. Rear entryway (second floor).
6. Rear stairs.

**Top right**
Facade, main office building.

**Right Middle**
Second floor, main office (drawing).

**Bottom Right**
First floor, main office (drawing).

At the bottom there are two measurement scales to show lengths.  Both mark units called *sazheni,* a length of about 2.16 meters (or roughly 7 feet.)

For the post-yard (bottom left), the key runs from 1-10 *sazheni,* or about 70 feet. 

For the main postoffice building (bottom right), the key runs from 1-5 *sazheni,* or about 35 feet.


[^1]: 'Postillion' is today an archaic word in English, but in its original meaning it mean the rider who led a team of horses, often riding one of them.  This role, in Russia, would have been fulfilled by local people serving the relay, that is, *iamshchiki*.  In the nineteenth century, *pochtal'ion* would increasingly come to be used interchangeably with *pochtar'* (the original word used in Russia for mail carriers or 'postmen').   But in this drawing, these are two different roles, as can be seen by the existence of one room (bottom right) for postillions, and another (inside the main office building) for "travelers and postmen (*pochtarei*)."
