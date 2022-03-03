---
title: The Challenges of Card Wall Management
excerpt: "is it really that tough?"
tags: 
  - card wall management
  - tech notes
comments: true
---

Card walls are all the rage.  It seems every team, proclaiming to be 'agile' or 
following some form of 'agile', has a card wall.  Although, in most cases, I do not see 
these teams actually knowing why they have a card wall or even what they are supposed 
to do with the wall... or the cards.  I would suggest dismantling and removing the card wall... 
if the team doesn't understand why they have a wall or the value of having the wall.  Not knowing why, 
will just result in the team not seeing the benefits and not using the wall.

So... now that I have suggested throwing your card wall away, maybe I should spend some
time trying to explain and inevitably convincing you otherwise.
Please keep in your mind... many teams are successfully delivering software... and they continually have issues
with the purpose of the card wall and it's mechanics.

---

The card wall should:
- bring the team together
- give the team a place to congregate and discuss the status of the project, which is inevitably the status of the team.
- improve the communication of the team.  This improved communication aids in the removal of blocks and decision-making.

A well-executed card wall will provide the following: 
- what is the current commitment of the team
- what is the team working on, both... at a team level as well as at the individual
- who is working on what... are they working on too many cards... are they working at all.
- what are the current blocks... and the status of the block
- a snapshot of the team work.
- a visible workflow
- WIP (Work In Progress) limits used by the team... are they violating them?
- a backdrop for the stand-up

# Why is card wall management so difficult?

Because it is not easy.  Well, that seems like a dumb answer, but an answer 
non-the-less.  The management of the card is inherently difficult because 
there are so many moving parts.  Any good card wall will have the complete 
status of the team at any given point in time.  For instance: 

- the number of cards in the backlog.
- how many of these cards have estimates... hello ! they should all have estimates... cards should not be in the 
groomed backlog unless they meet the definition of done... which includes a proper estimate.
- how many of these cards are blocked... and by this I mean, truly blocked.  Not because someone 'special' isn't available
to work on the card... or someone is on vacation... or they are IN A MEETING.  But a real block.
- how many cards are in progress
- has the team violated their WIP limit
- is someone working on more than one card
- how many days has the card been in the 'in progress' column... replace 'in progress' with whatever columns your team has
- has a small story remained in a single column for too long
- is there a bottleneck within a specific column or columns
- how many days are remaining in the sprint/iteration
- which cards have been accepted

But, why is it so difficult?  We have still not answered the question.  It is hard mainly because the team needs to get on board with the purpose of the practice.  The card wall is not there to make your life difficult.  It is there to make things big and visible, which can be painful at times.  But, there to, in one spot, show all of the teams successes and challenges in the same spot, at the same time.  Sometimes, people do not like for everything to be 'out there' where everyone can see.  Stop making a big deal about what you do not want to show the world and use the board to accelerate teh team to a new level of productivity and success.

# Why do teams make the card wall such a constraint?

I do not know that I have the definitive answer to that question, but I 
can speculate.  They are scared of what information the wall will present
to the outside world.  If the card wall is a mess and the outside observer
(whether a passer-by or your manager) attempts to read the board... the 
confusion will limit their ability to decipher.  Please stop doing this.
A well-executed board will allow the status of the team to be bigger 
and more visible.  You are more capable of recovering from a bad situation when the rest of the team knows the issue and can react and provide
assistance.

# Who should own the wall?  

### the Business?... 

### the Scrum Master?... 

### the Technical Lead?... 

### the team?

In my world, the card wall is owned by the team.  The business is responsible for putting cards within the backlog... 
in priority order.  They should add/remove/rearrange as much as they like.  As soon as the card is removed from backlog to the 'in progress' column, the business has lost the card.  If the business decides a card, already in progress, needs to be postponed or cancelled... the team takes the points and gives the card back to the business.  If the business decides the card needs to be placed back in to the backlog (at some point)... reestimation needs to occur.  This is not to be considered a point collecting exercise, but the cost of context switching.

There are an infinite number of possible layouts, and should be determined by the team.  Here is a basic layout I would start with.

Backlog | In Progress | Ready to Test | Tested | Ready to Demo | Accepted

---

# Backlog
Cards that meet the 'definition of ready' (defined later).  But in general... cards that are well defined, thought out and ready for someone to work... NOT cards that are blocked in some manner.  NO Missing Acceptance Criteria !!!

# In Progress
Upon entering this column... an entry conversation should occur.  I will leave it up to the team to define the participants, but the entry conversation is key and should not be skipped.  Many teams call this entry conversation... the 'three amigos' conversation... a developer (pair), a tester and a product owner... or some similar combination.  After this clarifying conversation... the card can actually be considered 'in progress'.

This column should be where all of the cards, that are currently being worked on, are located.  A reasonable WIP should be defined and all cards currently 'in progress' by the team should be in this column.  This means everything (every user story).  If a team member is working on 'something'... that 'something' needs to be put on a card and placed in the 'in progress' column.  When a team works on tasks outside the scope of the team space and are not managed on the wall... therse are generally the teams that never meet their commitments or the team that is continually finding themselves in the middle of a death march.

# Ready To Test
Development has completed the user story... test driven of course... and verified all of the acceptance criteria are met.  This might (should) include sitting with a tester and verifying the user story is delivered as requested.  The user story is now ready to be picked up by the testing team and verified... not on a developers machine, but the testing environment... the environment the application is automagically pushed to by the continuous integration process.

Let's work from left to right.

---

# Some Key Concepts Associated with the Card Wall

## definition of ready
this is a tough one.  The definition of ready should be 'what' the team agrees upon as a litmus to determine if a user story is ready to be worked by the team.  A user story should not (and in my world, can not) be added to the groomed backlog until all of the terms of the 'definition of ready' have been met.  Skipping, or worse... ignoring the DOR can cause lots of problems.  Here are a couple examples of what might be contained on the DOR...

- all acceptance criteria defined
- story sized
- all external dependencies identified
- clear description of business value
- etc.

## dots on cards
This is a personal one.  I like each team to put small indicators on each card at the completion of standup each morning (or whenever you have daily standup).  Each column on the card wall is assigned a different color indicator... including a way to mark the occurence of stand up and if a card is blocked at the end of standup.  For example... if a card is moved from 'backlog' to 'in progress'... at the completion of the next standup... a 'red' dot would be placed on the card (if the card was still in the 'in progress' column).  Each column is treated the same, but with it's individual color.  These dots allow for the daily analysis of which cards are stalled and which cards need assistance.  All of the cards should be analyzed in order to determine patterns over time.

## names on cards
This one seems pretty straight forward to me.  Each card on the wall should have a pair of names (you are pairing... right?).  The names are a great way to know who to ask when you have a question about a card.  It also helps to know when someone needs something to work on.  Also... it helps to know when someone is violating the teams WIP limits.  Please put names on the cards.

## blocked cards

## excursus

> put the excursus definition here

This one is mine... I invented it.  The 'EXCURSUS'... a divergence from the main point of topic... or in my mind... 'things' you want to talk about after the standup is complete.  These can be...

- information about an upcoming meeting
- a 'teachable' moment
- reminder about an upcoming holiday
- a tech moment

## swim lanes (WIP)
If you find yourself in a team space where the team is unable to manage their work in progress... introduce a swim lane.  If a column on the card wall has been limited to a certain WIP limit... divide the column into the same number of sections and only allow each section to have a single user story at a time.  The team will first push back, but it will be very visible when the WIP limit is being violated.

## days remaining
Pretty simple... the number of days remaining in the sprint.  It is nice to be able to look at the board quickly and see how many workable days remain.

## expected / accepted
Another pretty simple one, but powerful information.  Expected number of points to be completed by the end of the sprint... and the number completed.  This one really works with the 'days remaining'.

## business backlog (ungroomed)

## talk to the wall
Each pair on the team should speak to the cards on the wall.  This forces each pair to only work on 'things' that are being managed by the wall.  It also allows the rest of the team to remain focused on which column the cards is currently contained and if the pair needs immediate assistance to complete the card.

Let's talk to wall from right to left and bottom to top.

## drag cards
Cards should be added to the card wall... when someone on the team is pulled from the team space to work on something else.  Any work, completed by the team, not directly associated with the team (production support, helping another team, etc.) should be put on the wall (hours are fine).  These cards will allow for the proper analysis (at the end of the sprint)... especially when the team commitment is not met.
