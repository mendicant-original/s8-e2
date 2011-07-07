If you've only ever played family board games such as Scrabble and Monopoly,
you've missed out on a whole world of geeky goodness. There is an entire
subculture dedicated to fiendishly complex strategy games that are a ton of fun
to play and also serve as a great way to exercise the same sort of logic and
reasoning that you need to use to write good software. Every time I play one of
these games, I think about what it must take to actually design them and usually
end up with a headache.

For this exercise, you'll be taking inspiration from a pair of board games,
"Ticket to Ride" and "Steam", and then working to come up with a game engine
that is inspired by them. Please start by watching the following two videos so
that you can understand what the games are about.

  * <http://www.youtube.com/watch?v=f6Prr7iSt58>
  * <http://www.youtube.com/watch?v=S6YMCVg2_Ak>

The guidelines below describe what you're expected to do for this assignment.

* Your goal is to first come up with a set of rules for a train game inspired
by Steam and/or Ticket to Ride, but without directly copying the ideas of those
games. Once you have those rules figured out, you are expected to build a game
engine that enforces the rules and could be used to build a playable game
without too much effort.

* You are not expected to build a fully functional game complete with a full
event loop and user interface, but you should have examples that are detailed
enough to show how such a game could be built on top of your engine. For
example, you could create a script that runs on the command line simulating a
few player actions and then outputting the state of any relevant domain models.

* Both Steam and Ticket to Ride have some core concepts in common: Connections
between cities, ownership of those connections, and resources you need to
collect in order to build those connections. The game rules you come up with
should incorporate all of those basic concepts.

* Each game also has some special elements to it that add additional layers of
complexity or special cases on top of the core concepts. The game rules you
create should have at least a few of these special elements to keep things
interesting.

* You can and should discuss this problem with other students in the session.
While each student is expected to do a non-trivial amount of modeling for this
assignment, and we expect that no two students will have identical rulesets to
work on, there is a good deal of overlap in the overall design of games like
this as well as in some of the implementation code for various core structures
(such as a deck of cards). You are encouraged to share code with one another as
much as you'd like, as long as you have a large enough non-trivial portion of
your program that is your own work.

* This is the challenge problem for this session, so don't worry if it seems
complex. It is as much about requirements discovery and product development as
it is about writing functional code. Be sure to ask questions as they come
up, and simplify the problem as needed to get to a point that you feel you can
work on it. If you get stuck, just let us know and we'll help you out.
