# Raffle-app
It is a simple raffle app
It has following functions:

A way of creating a new raffle and saving it.
o At a minimum, a raffle should have a name, and description.
- A way of selling tickets for a raffle.
o At a minimum, tickets should have a price, number, purchase date/time, and be associated with a customer.
- A way of drawing a winning ticket/tickets at random.
- A way of listing all raffles.
o Including a way of deleting raffles that haven’t been started yet.
- A way of listing all tickets for a raffle.
- A way of editing raffle settings.
o Change name or description (note that some settings in the additional requirements below should be restricted for editing after the raffle has started—i.e. at least one ticket has been sold).
- A way of editing customer details on a ticket.
o You do not need to implement deleting a ticket.

In margin raffles, tickets should be given out in a random order (“normal” raffles, usually have tickets given out in order, e.g. 001, 002, 003). This is to prevent an advantage for buying tickets early (as margins tend to be lower numbers).
You will need a maximum number of tickets implemented for this, in order to select at random.
No two customers may have the same ticket.
If no customer has a ticket matching the margin at the end of the game, nobody wins.
