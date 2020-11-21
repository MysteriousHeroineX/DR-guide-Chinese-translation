### Chapter 2

# Part Two: Orienting Corners and Getting Good Edges

Once you have found a good EO start (remember there could be none), the next step is the actual domino reduction. The best approach to get all 4 good edges and the CO is to try and solve these two problems at the same time, saving moves. The are two sets of cases that can occur. If you have to deal with both E-edges and corners we call these Domino Reduction Triggers. If you have to deal with just corners or E-edges or you have both but EO is missing, we call these Partial Domino Reduction.

## 2.1 DR Triggers

Let’s look at the most simple one: Take a solved cube and apply R U2 R’. If you look at the cube you can see that you have 4 misoriented corners and only 1 bad edge. From this position, you can complete the DR in various ways, but the shortest ones are:

>R U2 R or R U2 R'
>
>L F2 L or L F2 L'

You can easily remember this case by looking at the position of the U/D stickers: the ones near the U/D edge form a “bar”, the ones near the E-layer edge form a “column”. Here are all of the most useful triggers we know of, assuming the EO is done on F/B with white on top.

>2 Corners, 1 Edge - WV
>
>L' U' R U L R'
>
>L R U' R' U L
>
>Other Variations

These kinds of triggers are very difficult to spot and setup in few moves. When you find yourself in a 2c1e case you may want to execute some moves to get to another case.

>**3 corners, 1 edge - F2L**
>
>R U R or R U R'
>
>R U’ R or R U’ R'
>
>L' U L or L' U L'
>
>L' U’ L or L' U’ L'

These can be seen as simple F2L cases.

>**4 corners, 1 edge - Column & bar**
>
>L'U2 L or L'U2 L'
>
>R'F2 R or R'F2 R'
>
>R U2 R or R U2 R'
>
>L F2 L or L F2 L'

These are the ones from the example. To set them up, focus on making the bar in front and the column on top at the same time.

>**4 corners, 2 edges - Conjugate and Solve**
>
>R or R'
>
>L or L'

If you have all the pieces in the correct position on the same face, DR can be achieved with a single move. Focus on making two columns with the E edges on U/D and bring them on the same layer. Pay attention to U/D edges to be on the same layer too!

All the other combinations of number of bad edges and misoriented corners lead to one of the above with a few moves.

The best way to learn the triggers is to figure out a personal way to recognize them and play around with them a little bit. During your first tries, take a second solved cube and use it to take some DR triggers as reference and see if you can find the way to set them up on your scrambled one.

At first you could find this very hard. Here are some examples to help you figure out the reasoning behind achieving DR.

>**First EO - Example**
>
>Scramble: R' U' F D2 R2 B2 D2 R2 B' F' L2 U' F2 U2 L D U' F' L' D' R2 U R' U' F
>
>U' F // EO (F/B) (2/2)
>
>(R B2 L2 B2) // setup to trigger (4/6)
>
>(D' L2 D' ) // DR trigger (3/9)

U’ F // EO (F/B)

Use NISS and look at the inverse scramble. With a z rotation you can easily see you are in a 4 corners 1 edge case (the orange-blue edge should not be in the E layer). Your aim is to set-up the Column & Bar case: the bar with the orange-blue edge, the column with the white-blue edge.

(R B2 L2 B2) // setup to trigger

*R - joins an orange sticker with the L/R edge forming a semi-bar*

*B2 - joins a corner with the E edge to form a semi-column*

*L2 - completes the bar*

*B2 - completes the column*

Now most of the work is done. Notice how moves of the U/D layers (in this case R/L) and double moves of the other layers don’t affect the number of oriented corners or of good edges

(D’ L2 D’) // DR trigger

We could have used a variation of the trigger, e.g. U F2 U.

Ideally you should check every option but considering you only have one hour in official attempts, you should choose the trigger that leaves you with the most blocks or with easy to solve corners. The second one is crucial in DR finishes, but we’ll get to that later. There are two other ways of achieving DR from that EO on the normal scramble that use the same concept of this setup.

>U’ F //EO
>
>R2 L2 U2 L // setup
>
>U L2 U’ // trigger

>U’ F //EO
>
>R’ L B2 R // setup
>
>D L2 D’ // trigger

These examples make use of a double move (U2 in the first one and B2 in the second one) to both setup some corners and move the bad edge in the correct position. Before this double move, the position of the edge would not have worked with the corners to trigger the DR.

>**Second EO - Example**
>
>Scramble: R' U' F L2 B2 R2 U2 F D2 B' L2 F' D2 U B L' U2 F' R2 B2 U' R' D R' U' F
>
>B' R' D' L' // EO (R/L) (4/4)
>
>F or F' // 4c2e -> 3c1e (1/5)
>
>(D' F2) // setup (2/7)
>
>(B' U' B') // DR trigger (3/10)

B’ R’ D’ L’ // EO

F / F’ // 4c2e to 3c1e

Both F and F’ end up working for our DR setup. Look at the inverse with NISS. Your aim is  now to try and setup one of the F2L cases (3c, 1e). To get a better idea of what you are going for, apply L’ U L on a solved cube.

(D’ F2) // setup

*D’ - moves a yellow sticker to form a semi-bar with U/D edge*

*F2 - moves the last corner to form a semi-column with E edge*

(B’ U’ B’) // DR trigger

DR is done!

## 2.2 Partial Domino Reduction

Sometimes, after you complete a DR step you may get what we call a Partial Domino Reduction, or PDR. It’s “partial” because you already have two of the three steps needed for DR, solved: CO, E-layer or EO. In this section we will go through all the possibilities.

Remember that a perfectly valid option with PDR is to keep going with the solve as if you had DR and fix everything with insertions at the end.

### *2.2.1 PDR in which you have CO and EO*

**1 bad edge**

There are two ways to deal with this case. The first one is to insert a commutator, either during the solve or at the end when you have a full skeleton. Edge commutators may cancel more than average in DR solves so it would be better to leave this at the end. Nonetheless, if you decide to insert the commutator while setting up the trigger, then you must pay attention to what edges you are cycling. For a 3 cycle the only valid options are:

Bad edge → E-edge in the U/D layer → Good edge

Bad edge → U/D edge → E-edge in the U/D layer

The other option is to insert a slice that swaps the bad edge with the last E-edge and either two U/D edges or two good edges. Here is an example of this by Sebastiano Tronto:

>**First PDR Example**
>
>Scramble: R' U' F U' F2 U' F2 L2 U' B2 D2 F U2 B' D' B D' F2 R' U' L' B U2 R' U' F
>
>F U D' R // EO (4/4)
>
>F // 3e1c (1/5)
>
>L2 U' * B U' B' //1e (5/10)
>
>* = U' M2 U (3/13) // DR

**2 bad edges**

>**Break & Solve**
>
>R' E2 R or R E2 R’'
>
>Other Variations

Your goal is to form a column with the E edges on the opposite face as the 2 bad edges and then swap them with R’ E2 R and variations. As in the previous case, you can insert a slice move in your solve that swaps the 2 bad edges with the two E-edges. R’ U2 D2 L = R’ E2 R is in fact the easiest case of setup to a single slice.

**3 or 4 bad edges**

This is not a very good case but you have a few options to consider:

-You could insert two slices that swap the bad edges with E-edges.

-You could perform a single move that takes you either to a 4c1e case or to a 4c2e case.

-You could keep on going with your corners first solve and insert the edges when you have a full skeleton.

If none of these seem to have good continuations, you should start looking for a different DR

### *2.2.2 PDR in which you already have E-layer and EO*

**2 bad corners**

>**Fake Swap**
>
>R U' L2 U R'
>
>Other Variations

Like the 1e case, this can also be tamed inserting a commutator either in the setup or in the  skeleton at the end of the solve.

**3 bad corners**

You can insert a sune or a 3-corner commutator. Keep in mind that the sune does a 3 cycle of edges as well, so the same rules that were explained in the ”1 bad edge” section for which edges can be cycled apply here.

If you decide to insert a commutator during the setup phase, you should go for the classic 8movers (pure). If you decide to keep on solving with PDR and insert the corners after you have a full skeleton, in section 5.1 we will talk about ”DR special” algorithms that may cancel more moves.

**4 to 8 bad corners

It’s better to look for another DR

### *2.2.3 PDR in which you already have CO and E-layer*

**0 corners and 0 edges**

You can use M’ U M, M’ U M’ and other Roux-like EO’s.

In this particular case you already have 4 good edges and all the corners oriented but you don’t have EO. To achieve DR you need to orient the edges using the S and M slices like in the second to last step of the Roux method.

Alexandre Campos has a nice document (https://docs.google.com/document/d/1oZwr2aSllFBL5lhbLTiWKQWplfk4i0LN0wA0uskeLJs/edit?usp=sharing) that collects a lot of corner-PDR and DR solves.
