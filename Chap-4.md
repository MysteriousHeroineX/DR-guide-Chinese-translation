### Chapter 4

# Part Four: Solving Methods

After you reduce the cube to a domino, you are not done yet! The last step of the DR solve, the “finish”, is where all the magic happens. You can imagine the DR as a solid tree trunk with different branches: CF, Slice insertions, HTR reduction and many more but for each solution only one of these has the golden apple hanging at the end of it. In this part of the guide we’re going to present you the basics of the most used methods to finish a DR. Once again, examples are the best way to learn.

To get started, you may want to get your hands on a Domino Cube (2x3x3). This can be solved with only U, D, L2, R2, B2, F2 moves, and is exactly the reason for the name Domino Reduction. Solving the Domino cube is a good way of practicing finishes although we don’t suggest using domino cube algorithms since they don’t work well for FMC.

## 4.1 Method 0 - Normal Skeletons

These are the type of skeletons you will get from “normal” attempts. The only difference is that with DR you can expect edge insertions to cancel a bit more moves than average. This is due to the high number of opposite moves in the skeleton and because, in general, the best edge insertion algorithms (e.g. 6 move 3e cycles, or easy 2e2e) already have EO.

>Normal Skeleton
>
>Scramble: R' U' F D' B2 R2 U' F2 D' F2 U B2 R2 F2 L' B F' R2 D L F2 U R' D2 R' U' F
>
>(B') U' D2 B // EO (4/4)
>
>D' L2 F2 U' // Setup (4c2e case) (4/8)
>
>L' // DR trigger (Conjugate and solve) (1/9)
>
>F2 D2 L2 (L2) // Blocks (4/13
>
>R2 U F2 U2 //3c4e (4/17)
>
>Skeleton: U’ D2 B D' L2 F2 U' L' F2 D2 L2 R2 U F2 U2 L2 ° B
>
>° L2 U2 R2 D2 R2 £ U2 (6-4/19)
>
>£ R2 U' L2 U R2 U' L2 U (8-3/24)
>
>Solution: U' D2 B D' L2 F2 U' L' F2 D2 L2 R2 U F2 R2 D2 U' L2 U R2 U' L2 U' B (24)

Setup explanation:

D' L2 F2 U' // setup (4c2e case)

*D' L2 - forms a column with the red-green edge*

*F2 - brings one U edge on the L layer and completes second column with the red-blue edge*

*U' - brings both columns on L layer*

Now Let’s get to the exciting stuff.

## 4.2 Method 1 - Corners First

Attila Horv´ath usually starts his solves orienting and solving corners while trying to solve as many edges as possible. This technique can be good for DR as well if the corners are easy to solve.

You can find more info about corner first as a method here: https://www.speedsolving.com/wiki/index.php/Corners_First

This approach can be very good for DR starts since corner insertions can be very inefficient. Most of the times you will find solutions for corners that influence the edges in different ways, be sure to take advantage of that. Also note that you don’t necessarily have to solve corners relative to centers but only to each other. The downside of this method is that solving corners will be sometimes very difficult.

>CF example
>
>Scramble:R' U' F L2 B2 R2 U2 F D2 B' L2 F' D2 U B L' U2 F' R2 B2 U' R' D R' U' F
>
>B' R' D' L' // EO (4/4)
>
>F’ (D' F2) // Setup (3/7)
>
>(B' U' B' ) // DR trigger (3/10)
>
>L2 U B2 D' R2 U' D2 // Solves corners and leaves 5e (7/17)

Many world class solvers try to solve corners as soon as they get a good enough DR start. If corners are easy to solve then you can focus on finding nice insertions for edges: as Sebastiano Tronto once said: “DR + easy corners = insert right away!”. As I said before, you can expect these to cancel more than average on edge skeletons because of opposite moves.

There isn’t a specific method to consistently solve corners in few moves, it’s really scramble dependent. Some tips we can give you are:

- Study some CF-users solves to learn some tricks.

- Try to start solving two opposite pairs of corners together. If you’re lucky enough, the other  4 will be easy to solve.

- Scramble a 2x2 and practice with it (remember that you’re not allowed to use it in competition).

- If you know some short CP algorithms you may find them useful in specific occasions. You’ll find lots of CF solves in this document too.

## 4.3 Method 2 - Block building and linear endings

A linear ending is a DR finish that relies mainly on intuition. You first start by building some blocks and you finish. . . by building other blocks. Linear endings may seem the easiest to master but it turns out that solving a Domino cube using only your intuition is not a simple task. That’s because there isn’t a standard approach to linear endings. You just “put pieces together” to solve the cube. Here are some tips:

- As usual, try to make squares or a 2x2 as a starting point.

- When you set up your DR trigger, keep an eye for possible squares/blocks to form. It’s also possible to start the solve with some random blocks + EO and then -setup the DR.

- Avoid diagonal corner swaps while making blocks.

- Try to influence the E layer while moving around pairs and pieces. This can make the difference towards the end of the solution.

- After you’ve made nice blocks, the nice ending should be easy enough to see. If you can’t find it in one or two minutes, go back and change your blocks.

- Speed is key. As you get faster to find DR’s, you should get faster in solving blocks in different ways. This would often lead to a nice ending.

- Try to make blocks un U/D layers and avoid solving E-layer.

- Be creative!

- Sometimes destroying already existing blocks that are in the way, can lead to a better block-building in the end.

Block-building is not an exact science, and this is true not only for DR. Usually block building can turn out to be very frustrating but with DR things are a bit easier. Try to “spam finishes” and quit only when you are really convinced your start has no good continuation.

Here is a solve by Sebastiano Tronto in which he uses this type of finish. You can get the importance of the tips above and you can feel the power of a good DR start.This is the same scramble in which Harry Savage got his 17 WR single. We’ll look at his solve in the next section.

>BB example
>
>Scramble: R' U' F D' L2 B2 R2 B2 U F2 D U F2 R2 F D R2 B L D' B2 R' D' F2 R' U' F
>
>R L' D' L // EO (4/4)
>
>(R2 F) // DR, 2e-4c case (2/6)
>
>(L2 D R2 U2 R2) // Same blocks (5/11)
>
>(U2 D R2 D B2 U' D2) // Finish (7/18)
>
>Solution: R L' D' L D2 U B2 D' R2 D' U2 R2 U2 R2 D' L2 F' R2 (18)

Explanation:

R L' D' L // EO

(R2 F) // DR, 2e-4c case

*R2 - setups the columns on F layer*

*F - triggers the domino*

This Domino Reduction is clearly very lucky and “easy”. Sebastiano said he found it by accident as he was just trying to form a square. Finding starts like this is not very common, in fact not every solve is a world record.

• First finish (19):

(L2 U F2 U' D' L2) //blocks

The general idea is to try to influence the E layer in a good way, while making some blocks. There are multiple options to make blocks on U/D layers. Ideally you should try them all and find the one that gives you the finish.

After some time, you’ll get very fast at it.

(U D2 F2 D R2 D' U2) // finish

Once there are some blocks, it’s time to put them together. Follow the E-edges movement and focus un U/D blocks, to goal is to solve both at the same time.

• Second finish (18):

(L2 D R2 U2 R2) // same blocks

Here, Sebastiano goes back to his solution and tries to improve it. He manages to make the same blocks again, influencing the E layer in a different way, but with one move less!

(U2 D R2 D B2 U' D2) // finish

The ending is technically very similar to the first one.

Comment by Sebastiano:

“At first I used (R2 F’) to make that extra square, but I could not finish the domino solve from there. Changing F’ to F gave an easier (in my opinion) but sub-optimal solve. I found the 18 in about 20 minutes total. The two solutions that I have found are the same if you disregard the E layer; I have tried improving it further with the same strategy, possibly leaving some E-layer edges unsolved and inserting them, without success.”

## 4.4 Method 3 - HTR solves

HTR, also referred to as H2, is the third step of the Kociemba algorithm and it consists of reducing the cube to a state solvable within the [ U2, D2, F2, B2, L2, R2 ] group. If you visit Ryan Heise’s site (click here!), you’ll understand that H2 is a very important step of the Human Thistlewaite Algorithm (HTA) as well, the human way of doing Kociemba. This case has been called in many different ways such as Double Domino, Domino on 2 axis or G3. For the purpose of FMC we’ll call it Half Turn Reduction or HTR.

It’s fairly simple to understand how to get to this state. As you did for DR, where you had only white/yellow stickers on the U/D layers, you have to put stickers of the same or opposite colour on each face. So: only green or blue stickers in F/B and only orange or red stickers in R/L. This is not enough though: you must also avoid diagonal corner swaps, otherwise the cube will not be solvable with the double moves group. Try to solve an N-perm with double moves only, you will give up shortly after. The best thing about this technique is that once you reach HTR, the cube is very easy to solve. That’s easier said than done. The downside, in fact, is that getting to HTR may require a lot of moves. On Ryan Heise’s site there are some sub-optimal ways to do it. Check them out if you want to examine this technique in depth. The very important thing though, is that you are able to recognise when you are close to HTR, so you don’t miss it, rather than knowing all the possible ways to set it up. It is pretty rare to get!

In the following example you can see how easy the finish becomes after HTR.

>HTR example
>
>Scramble: R' U' F D' F2 R2 F2 L2 D' U2 B2 U' B U2 R' U' L' F L F2 R' B R' U' F
>
>F B' R U' L' // EO on R/L (5/5)
>
>F' U2 R2 F // Setup to 4c-2e (4/9)
>
>U // DR trigger, Conjugate& solve (1/10)
>
>B' D2 R2 B' R2 B // 2e6e (6/16)
>
>Skeleton: F B' R U' L’ F' U2 R2 F U B' D2 R2 * B’ R2 B (16)
>
>Now use reverse NISS at *:
>
>F’ R2 L2 B' // HTR (4-2/ 18)
>
>R2 B2 U2 L2 F2 R2 D2 // Finish (7/25)
>
>Solution: F B' R U' L' F' U2 R2 F U B' D2 R2 F' R2 L2 B' R2 B2 U2 L2 F2 R2 D2 B' R2 B(25)

Explanation:

F' U2 R2 F // Setup to 4c-2e

*F' U2 - setups the first column and moves the second semi-column away*

*R2 - completes the second column*

*F - moves the two columns on the same layer*

B' D2 R2 B' R2 B // 2e6e

*B' D2 R2 - puts the corners in pairs*

*B' R2 B - solves the corners*

As you can see this is a simple enough case to solve. Reducing to double moves may also lead to better edge cases.

The former FMC 17 moves WR single by Harry Savage used HTR.

>17 WR - HTR
>
>Scramble: R' U' F D' L2 B2 R2 B2 U F2 D U F2 R2 F D R2 B L D' B2 R' D' F2 R' U' F
>
>R L' D' L // EO (4/4)
>
>(R2 F') // DR, 2e-4c case (2/6)
>
>U' R2 D' L2 D' L2 D // HTR (7/13)
>
>F2 U2 F2 L2 // Finish (4/17)
>
>Solution: R L' D' L U' R2 D' L2 D' L2 D F2 U2 F2 L2 F R2(17)

U' R2 D' L2 D' L2 D // HTR

*U' - First step towards HTR. Note that the F and R faces are “ready”. Now you must take care of corners to avoid diagonal swap cases*

*R2 D' L2 D' - Follow the Orange-Yellow-Green corner. these moves are a setup to put this specific corner with an orange semi-bar while move the green/blue stickers out of the way. The goal here is to make bars of opposite colours and then align them correctly*

*L2 D - does the job*

Getting an HTR simplifies the situation a lot, but sometimes it may be difficult to understand how to finish the cube right away. When you get to this state, play with it for a while: the solution must be close!

Also note that the “R2” in the HTR step is necessary. If you take it out you still end up with the right colour pattern but you have a diagonal corner swap because you are left with 3 corners to solve. (Do U’ D’ L2 D’ L2 D L2 and see it for yourself).

The last example is a solve by Chong Wen.

>HTR example by Chong Wen
>
>Scramble: R' U' F D' F2 U' R2 D R2 U L2 R F2 U' B L R U L2 F2 U R2 U' R' U' F
>
>F (F2 U F’) // EO (4/4)
>
>(L' U2 D' L D' L’) // DR (6/10)
>
>(R2 U2 B2) L2 // 223 (4/14)
>
>L2 D F2 D' L2 B2 D' R2 D B2 // T perm to HTR (10-2/22)
>
>B2 D2 F2 D2 B2 // Finish (5-5/22)
>
>Solution: F D F2 D' L2 B2 D' R2 D' F2 D2 U2 R2 L D L' D U2 L F U' F2 (22)

Another very easy finish after HTR! 
