# Capstone Project: The Evolution and Ongoing Decline of Yu-Gi-Oh

## Background
Yu-Gi-Oh is a japanese trading card game, widely regarded as among the top three tcgs in the world with Pokemon and Magic the Gathering.

I am a long time fan, so the game is near to my heart, and I wanted to use hard data to analyze some concerns I have with the game.

## Questions

Yu-Gi-Oh Master Duel, a video game that is the official digital way to play the game, released two years ago. 
In that time it has lost 90% of its average player count

Video essays of longtime players quitting and new players struggling with the game's complexities are concerningly frequent.

Master Duel itself is free to play and very generously monetized, so the issue should hide in the game itself.

In this analysis, I set out to answer three questions to check if the most common complaints are grounded:
- Is the game difficult for newcomers?
- Is the game overly complex even once learned?
- Is the physical card game too expensive?

## The Process
Dataset provided by the free card database API of fan site YGOProDeck.com

Using my existing knowledge of the game, I will break the cards into smaller datasets to compare qualities of the cards.
By visualizing the cards as data points, I can reasonably track the game's complexity by referencing the data with the game rules.

## The Results

### Newcomers and the Learning Cliff

I will open this with the knowledge that Yu-Gi-Oh is different than most TCGs, as it doesn't have a concept called 'set rotation'.
Essentially what that means is that all 12.5 thousand plus cards can be played in an official tournament setting, provided it isnt banned.

Further, there is no play cost in Yu-Gi-Oh, no mana or energy. So long as a card says you can do something, you can do it.

With this in mind, the best way to track complexity in Yu-Gi-Oh over time is to track the average word count on cards released over the years.

The answer is that cards word counts have been steadily increasing, alongside new types of cards and new mechanics attached to them. 
With the entire card pool being accessible for use, newly released cards need to continuously be strong than the older ones to both keep the game fresh and the products profitable. This has led to something called 'Power Creep', where eventually new cards are orders of magnitude better than ones from just five years prior.

This points to the answer that, yes, the game is very unforgiving to newcomers. The skill ceiling is high and the game itself can be very unintuitive as the best decks continually require more reading.

“Something in your brain clicks, and you just stop. You just say ‘[...]Do what you must, I will trust that you aren’t cheating’.”    
- Content Creator MBT Yu-gi-oh, sympathizing with card game streamer Rarran’s misfortune after trying Master Duel

### Game Complexity and Losing Fans

A common sentiment I hear about people who have quit Yu-Gi-Oh is that 'new type of monster card X ruined the game'.

These are often hyperbolic, but not without grounds.

The with the high skill ceiling only getting higher as time goes on, existing players may find themselves falling too far below it to catch up.

Courtesy of the effect text bloat of recent years, cards that do similar things on the surface can be worded in wildly different ways, and then differ in other uses. 

Yu-Gi-Oh's effect writing is called 'Problem-Solving Card Text', and unlike other games it does not use many keywords to shorten the word count. 

One of the most useful effects a card can have is to add a card to your hand, for example from your deck or graveyard. 

Effects that add to your hand have increased by orders of magnitude since the game's early days, and those cards are capable of doing more and more every year.

Banishing is a very old mechanic, nearly as old as the game itself. Yet, the term for where banished cards go, a player's 'Banishment', was created without hyperbole a week prior to writing this report.

In terms of a monster card's stats, there is very little ways to intuit what a card might do just from type or attribute. Any given quality of a monster card doesn’t give any indication of how they might interact with other cards. No two decks of 'Dark Fiends' play exactly the same.

Even if you’re an established fan of the game, it’s steadily getting more difficult to play as stronger cards that do more just keep getting printed.

### Worth More Than their Weight in Cardstock and Foil
The API has many prices listed, I took the lowest from the two most trusted single card vendors in the community:
- TCGPlayer
- CardMarket

The most important cards of the strongest or 'meta relevant' decks often have high price tags attached to them.
For the purposes of this analysis, I took cards from the current meta decks:
- 'Fire King',
- 'Labrynth',
- 'Kashtira',
- 'Spright' 
Since the decks are so strong there is high demand for their best cards, and as such few of them have prices under a dollar wth some even reaching twenty.

Similarly, there are 'Staple' cards, ones that could concievably be played in anything because they are generically good and their uses come up often.

Because these cards are so individually strong, they often have high demand as well, which can worsen if they were high rarity or if they haven't had a printing in a while.
For example, 'Accesscode Talker' is an incredibly strong card hasnt had a reprint in a year and has never been printed lower than 'Ultra Rare'. As such, it also demands a minimum of $20 a card.

I opened this presentation by saying Master Duel was very fair to players who didnt want to spend money on the game, but when the physical card game has such steep prices, it’s easy to see why someone might quit.

## Conclusions

It pains to say this for a game I love, but many of these complaints have evidence to justify them in the data.
There are two many mechanics as it stands for new players to comfortably start playing without issue.
The constant powercreep means any player's favourite deck is just waiting to become obsolete.
The indirect cost of entry for professional play from the massive prices of optimal decks could easily scare off casual players.

## Solutions

Konami is already aware of these problems. 
The game does have 'The Forbidden and Limited List', which restricts how many of what cards can be played in a deck, but this has steadily been failing as new cards end up outclassing these older ones that have been hit.

There are alternate formats of the game:
- Speed Duel a simplified version,
- Rush Duel, a sort of reboot that hasn’t been brought to the west yet.

These are novel in concept, but does not fix the wider issue of the existing game.

I’ve mentioned set rotation a few times now, when older card sets are taken out of the game as new sets are released. This is a contentious topic in the yugioh community, as some players enjoy that every card is legal and Konami frequently pays omage to the game’s history by giving old fan-favourite decks new cards to make them viable in the modern game.

I believe officially supporting the game as it is now as an ‘Unlimited’ format alongside a new and separate rotating format would be the best of both worlds. It would allow new releases to have their power toned down while still allowing people to play the massive card pool.
