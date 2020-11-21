### Chapter 3

# Part Three: Alternative Approaches

This guide will be mainly focused on the three-step method described in the previous sections: EO first, then setup to DR trigger and finally the trigger itself. This method is the most common and probably the most reliable to get a DR within 14 moves. With 6 different possibilities (2 for each EO) that become 12 if you also check the inverse with NISS, there is a high chance to get a decent solve. This doesn’t mean you should use DR in every attempt though. With practice you will get fast enough to spot triggers in a reasonable amount of time. This allows you to add a “DR check” in your FMC routine. Try to apply DR whenever possible, but don’t try to force it.

If, instead, you want to focus mainly on DR, here is some advice:

-Try keeping track of corner orientation doing EO, possibly influencing it.

-Pairs or pseudo pairs, made by joining same or opposite colours together, can lead to a better trigger case

-Each EO has two possible endings, try both (e.g. F/F’)

-Try influencing E-layer edges during EO, you should end up with at least 2 good edges to get a good DR.

Different approaches consist in joining some of the steps together or changing their order. In the next sections we will talk about them very briefly since a lot of this stuff is still unexplored.

## 3.1 Orient First

In this paragraph we’ll show you some solves by Attila Horv´ath. He applies DR orienting corners first and then orienting and fixing edges. Orienting corners at the start of a solve can be tricky to learn for most cubers If you want to practice, scramble a 2x2 cube and try to orient all the pieces in the fewest moves possible. A few ideas to start are:

- Try to create corner bars and simultaneously corner columns.

- Understand how moves are going to affect the orientation of corners.

- Don’t bother about the position of edges or centers.

- Study as much example solves as possible.

- Remember that sometimes orienting corners can take lots of moves and it’s not always efficient.

Doing is better than reading. Follow along this solve by Attila!

>First CO Example
>
>Scramble: R' U' F R2 B' R2 B U2 B2 F' R2 B2 U B U2 R D B' U B2 L2 F L' F2 R' U' F
>
>(F R2 U R) // orient R/L corners (4/4)
>
>(D2 R' U D' F) // orient edges to PDR (5/9)
>
>R L2 D' R2 L2 U // DR (6/15)
>
>F2 R2 L2 D2 R' B2 R2 // Solved (7/21)
>
>Solution: R L2 D' R2 L2 U F2 R2 L2 D2 R' B2 R2 F' D U' R D2 R' U' R2 F' (21)

Explanation:

*F - creates a bar and a column*

*R2 - creates a second bar and second column*

*U R - orientates corners*

Remember that at the beginning, the position of the centers is not relevant: we want to orient corners in relation to each other. Once you have CO, the next step should be EO. This can be done in multiple ways, using slices to move edges around or breaking and fixing corners. As always, our aim is to solve edges in the most efficient way possible. If you orient edges with slices, you’ll find that edge skeletons are much easier to insert.

(D2 R’ U D’ F) //orient edges to PDR

This is a setup to E slice. It can be hard to see at first, but rules are pretty much the same of normal EOs. The only difference is that doing half turns affects corner orientation. That’s why you must pay attention to it and always perform the anti-setup to fix it. Also remember that centers are not relevant before EO but they are AFTER.

R L2 D’ R2 L2 U // DR

DR cases for orienting first are tricky. Here we have the basic one: 2 edges, no corners. You can solve this with the Break and Solve DR Trigger

F2 R2 L2 D2 R’ B2 R2 // Solved

Solving the cube after an orient corners first DR can be very easy, since we can go back and influence the corners’ solution and/or make blocks moving edges with slice to get a linear ending. This is difficult enough to do and requires practice.

There are three main advantages of using this method:

- Once you choose one of the three possible CO, you’ll have only one DR to check.

- You can immediately see if the corners are easy to solve.

- It’s very easy to influence edges during the CO steps using slices.

This method is at his best when you realise you can modify the CO a little to orient some edges and fix the E layer. The DR should then be a few moves away.

These are two more example solves. As always, try to follow bars’ and columns’ creation during corner orientation.

>Second CO Example
>
>Scramble: F R' F2 U' L F R F' D B' D' L2 B2 U F2 R2 U' L2 B2 U B2
>
>R L' F B' L' U' R' B L' // Orient R/ L corners (9/9)
>
>Note that R L' F B' are useless to CO.
>
>F L' F B' U R2 F B' U2 L U D' B' // DR ( 13/22)
>
>R2 F2 L F2 L U2 L' R2 // Finish ( 8/30)
>
>Solution: R L' F B' L' U' R' B L' F L' F B' U R2 F B' U2 L U D' B' R2 F2 L F2 L U2 L' R2 (30)

Attila’s method is mainly focused on influencing the next step while doing the previous one. You can see the first step above as:

* B' L' F' U B' // CO

* M' S' // Influences edges orientation

Again, in this steps Attila inserts lots of slices to move edges around. This has two main reasons: getting to DR and creating blocks. Try to follow along ignoring centers position.

F ° U2 * D2 £ B2 L2 F L2 F D2 F ! // solves corners, leaves 6edges

*° : L' S' L - set-up to slice to moves some E-edges*

** : S' - set-up (moves an R/L edge)*

*£ : R E R' - set-up to slice to orient last edges*

*! : S2 - solves last 4 edges, 4 centers*

Next solve is by Sebastiano Tronto:

>Third CO Example
>
>Scramble: R' U' F U R2 D R2 B2 D' B2 L' D2 L2 R D U L2 F' U2 B L' B R' U' F
>
>U' B' U B // CO, corners 2 moves from solved (4/4)
>
>(D2 L F' R' L D) // DR (6/10)
>
>(R L') // 3e2e2e (2/12)
>
>Skeleton 1: U' B' U B * R' L D' L' R F L' D2 (12)
>
>* = B2 L2 B2 R2 F2 R2 // 2e2e (6-4/16)

Replace the last 7 moves with D' R L' F D2 to get a 5e case:

Skeleton 2: U' B' U B' * L2 B2 R2 + F2 R D' R L' F D2

* = E'

+ = [R' B' D' B: E]

## 3.2 Sledge/Hedge DR

Another method to obtain DR avoiding EO was suggested by Chong Wen but we couldn’t see it applied anywhere in any solve. Basically, this trick consists of using DR Triggers that influence EO too, thus saving some moves

>R’ F R F’ – 2 non-oriented U/D edges; 1 oriented E-edge; 4 corners
>
>F R’ F’ R - 2 non-oriented edges, one U/D and one E; 1 oriented U/D edge; 4 corners

As always, execute the inverse of this triggers to understand how corners should be positioned.

We think that practicing this is not worth it but it’s nice to know and think about it nonetheless. In our opinion it can be useful only if you find yourself in the perfect situation. Scrambles with only 2 misoriented edges and half of the corners oriented are not so rare, although most of times it’s convenient to just do EO.

Here’s an attempt made by one of the authors (Alexandros Fokianos)

>Sledge/Hedge Example
>
>Scramble: R' U' F R2 D' L2 U' F2 R2 F2 L2 U' F2 D F L2 U2 R F' D2 F U' L D U R' U' F
>
>(R’ L D’ L) // Orienting stuff (4/4)
>
>(B2 D B2 U2 B2) // Setup (5/9)
>
>(B L’ B’ L’) // DR trigger (4/13)

Setup explanation:

*B2 D - a column with E-edge is already formed. B2 D form a semi-bar with the misoriented U edge*

*B2 U2 B2 - simply setups the case. To follow this, keep the cube with blue front and white up*

It took me some moves in the beginning to correctly orient pieces to get the sledge case. Setup is not that hard but keep an eye for conveniently oriented scrambles. DR could be 7 or 8 moves away and this method is more efficient than doing EO for just two edges.

## 3.3 E Slice First

There is another way of getting to DR mixing the order of the steps.

This method is a bit on the difficult side but can become very powerful if used on the right scramble.

First, we fix the E layer, orienting some corners along the way. This becomes very easy if you  already have 2 or 3 good edges. Avoiding EO makes things a lot easier since you have no move limitations. The next step is CO. You can make use of the DR triggers we learned at the begging to move around the last E edge orienting corners.

At this point you have a PDR that’s missing EO. You can apply some Roux methods to get DR. In the best case, you will have only 4 misoriented edges that can be solved using M’ U M triggers. Even if using slices may seem inefficient, it can be useful later during edge insertions.

If you choose to apply this method, here are some tips:

-Try to influence EO while doing CO

-Play around with E-edges and choose different corners to orient

Here is an example:

>E-First Example
>
>Scramble: L' U B' D2 F' D' F2 R L2 D' F2 R2 D2 F2 L2 U' L2 D2 B2
>
>U2 D F // 3 E-edges + some CO U/D (3/3)
>
>D' U' L' D' L // CO + last E-edge (5/8)
>
>L R' F R2 B L R' // EO trigger to DR (7/15)

Setup explanation:

*D’ U’ – setups the case*

*L’ D’ L – DR trigger (except it doesn’t make DR here)*
