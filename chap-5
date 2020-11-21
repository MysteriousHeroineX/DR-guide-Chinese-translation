### Chapter 5

# Part Five: Tips & Tricks

## 5.1 Inserting Corners

As we have seen, the general approach to DR is to solve corners first and then fix the edges  with insertions. We will talk about different ways to do this in the next section. Sometimes solving corners is not  that easy though.

Skeletons like 3e3c, 2e2e3c or, obviously, 3c can then be viable options to get very good  results.

For 3 corners, there is the feeling that 8 move commutators cancel less moves on average on DR skeletons compared to regular ones, although we don’t think this has been proved yet. It would be interesting to explore this topic a bit more in the future. To face this problem, here is an example of a nice 10-mover highlighted by Chong Wen:

>R2 U’ R2 B2 D’ R2 D R2 B2 U
>
>B2 L2 U B2 U’ B2 L2 D’ B2 D

Both of these solve the same 8-mover 3 corner case in 10 moves but they seem useful especially in domino solves.

Note that you can replace all the U/D moves with their wide variants to get different algorithms. These were discovered with the new Insertion Finder so we personally don’t know if there are any other.

For 4+ corners, almost all skeletons are not worth it. We’ll let you keep crazy ones like 10 moves to 5c).

A special mention goes to 2c2c skeletons.

The first one is an algorithm we learned from Chong Wen, the other two are from Vasco Vasconcelos:

>R2 U’ Rw2 U F2 R2 U’ Rw2 U F2
>
>R2 L2 B2 D B2 R2 L2 F2 U F2
>
>U F2 R2 L2 B2 D B2 R2 L2 F2

These are very flexible: they can be shifted and their inverse solves the same case. You can also use the last two to solve edges as they are derived from the H perm!

## 5.2 Solving Edges

DR start + Corners first finish = edge insertion

It’s hard to get experienced in these, but, for the most part, you will be using the same three or four edge cycles and their shifts and mirrors, on top of the ones you use for a “classic” edge skeleton.

>(R2 F2 R2 U2) *2 - edge 3-cycle
>
>(R2 U2) *3 – 2e2e swap, and variations
>
>(Rw2 U2 Rw2 B’) *2 – edge 5-cycle

We’d like to spend a few words on 2-2 edge swaps, because it’s the easiest case to find mirrors, shifts and alternate versions of.

Take this sequence:

>L2 D2 L2 D2 L2 D2

You can turn it in a different algorithm that may cancel more by substituting the moves in [brackets] with their opposite:

L2 [D2 L2] D2 [L2 D2] becomes L2 [U2 R2] D2 [R2 U2] = L2 U2 R2 D2 R2 U2

Here’s a brief list of some easy to learn 2e2e cases:

• Classic 2e2e (2axis)

L2 (D2 L2) D2 (L2 D2) = L2 U2 R2 D2 R2 U2

or

(L2 D2) L2 (D2 L2) D2 = R2 U2 L2 U2 R2 D2

or

(L2) D2 (L2 D2) L2 (D2) = R2 D2 R2 U2 L2 U2

• M2 2e2e

M2 U2 M2 U2 = L2 R2 D2 L2 R2 U2

shift: (R2 D2) L2 R2 (U2 L2) = L2 U2 L2 R2 D2 R2

• Strange 2e2e (3axis):

L2 (D2 L2 F2) D2 (L2 D2) F2 = L2 U2 R2 B2 D2 R2 U2 F2

• T-shaped 2e2e (3axis)

D2 (L2 F2 D2) L2 (D2 F2 L2) = D2 R2 B2 U2 L2 U2 B2 R2

• Slicey 2e2e + shifted versions

M’ S2 M’ S2 = (L’ R) U2 D2 (L R’) F2 B2

shift: D2 L R’ F2 B2 L’ R U2

The following is an example on how these could be used.

>Edges Example
>
>Scramble: R' U' F L2 F2 L2 U F2 D2 L2 D2 U' L2 B' U L' R U2 F D U2 L' B R U'R' U' F
>
>L' R B // EO (3/3)
>
>(L' U2 L' ) // DR trigger, reduces to 4c-1e (3/6)
>
>U L2 B2 // Setup to Column & bar (3/9)
>
>L D2 L' // DR trigger (3/12)
>
>U' L2 D R2 D2 // 6e (5/17)

Note that there are different ways to solve corners. Try out some of them! The best way leaves 6 edges

Skeleton: L' R B U L2 * B2 L D2 L' U' L2 D R2 D2 § L U2 L (17)

*: R L' D2 R' L B2 // M’ U2 M U2 edge 3 cycle (2/19)

§: D2 B2 D2 L2 B2 D2 B2 L2 // Nice 2e2e swap! (5/24)

## 5.3 Free Slice

Inserting an algorithm is not the only way to solve edges.

The FMC community is going crazy about a new technique that is still under development. Since it uses slice moves to insert many edges in one or two moves in total, is commonly referred to as “slicey insertions” or “slicey shenanigans”. For the sake of simplicity, we’ll call it Free Slice (FS). The idea behind it is both simple and powerful. Take a solved cube and execute M2. The UF edge has swapped with the DB edge, the UB edge has swapped with the DF edge. If you can find a spot in your skeleton where you can insert a slice move solving 4 edges, you’ll save a lot of moves.

M2 also swaps the centers. This is not a problem if you know how to insert them. A center insertion will usually take up to 5 moves. Moreover, if you have more than 4 edges, you may be able to slice once to solve some and “slice back” in a different point to solve the remaining ones and the centers you offset the first time. We call slice back the insertion of the inverse of a slice previously inserted. So, if in a spot you insert S, a slice back would be an insertion of S’ further along the skeleton. With a few examples this idea will be easier to understand.

Center insertions are a bit tricky, I recommend reading Sebastiano’s guide to learn how to treat them.

Becoming fast and efficient with FS is hard and it requires a lot of practice. Here are some tips to get started:

- If you have 6 or 7 edges, look for a spot where a 180° slice leaves 3 or 4 edges unsolved

- Don’t worry about centers, you can fix them later.

- If you’re good at BLD, you can do a memo of the pieces and try inserting slice moves in  your skeleton without stickers to speed up your insertions - Enjoy yourself, be creative and study lots of example solves!

This section will have a lot of examples because it is one of the hardest concepts of the entire guide.

The first one is the current WR single by Sebastiano Tronto. If you want a visual explanation of the solve by Sebastiano himself, you can check his video: https://www.youtube.com/watch?v=I0yjjwxonEE.

>Free Slice Example
>
>Scramble: R' U' F D2 L2 F R2 U2 R2 B D2 L B2 D' B2 L' R' B D2 B U2 L U2 R' U' F
>
>(U D' F R) // EO (4/4)
>
>(L2 F' B2 U' B2 U' ) // DR, 4c-1e case (6/10)
>
>(R2 B F D2) // 5e (4/14)

(L2 F' B2 U' B2 U' ) // DR, 4c-1e case (6/10)

*L2 - forms a column with the E-edge*

*F' B2 - forms a bar with the B edge*

*U' B2 U' - DR trigger*

(R2 B F D2) // 5e (4/14)*

Pretty lucky ending: corners are solved in pairs and you just have to put them together. Note that there are different ways to do so, but R2 B F D2 is the shortest one that solves the most edges. Choose a finish that will give you a good balance of number of edges left and number of moves. 4 moves to 5e is pretty good.

Skeleton : (U D' F R L2 F' B2 U' B2 U' * R2 B + F D2)

* = U D' F2 D U' R2 //2e2e (2/16) .3cycle to a 2e2e case.

Take this new skeleton and look at the 4 edges left. Even without stickers, it’s easy enough to spot at “+” that all 4 of them are on the same slice . With a simple “E2” move you’lll solve the 2e2e cycle in just two moves!

Remember to rewrite all the moves following the slice in the new orientation of the cube, F D2 becomes B D2.

Skeleton: (U D' F R L2 F' B2 U' B2 U' U D' F2 D U' B + F D2)

+: U2 D2 // E2, FreeSlice to 4x (2/18)

You’re now left with a center insertion.

Skeleton: (U D' F R L2 F' B2 U' B2 U' U D' F2 D U' # B U2 D2 B D2)

# = E M2 E' M2 // centers (2/20)

Once again, remember to rewrite the moves after the center insertion in the new orientation.

Temporary solution: D2 F' D2 U2 F' L2 R2 U' D B2 D B2 U B2 F L2 R' F' D U' (20)

Sebastiano then used an advanced technique to get the 16 but we’ll explain it in another section. This “lucky” solve shows the potential behind mastering DR along with CF + FS techniques.

The second example is a 3-edge FS solution by Tommy Kiprillis:

>FS Example 2
>
>Scramble: R' U' F L2 U2 L2 B2 F' L2 R2 U2 B F2 R U L2 R2 B' L2 F D' F R F' R' U' F
>
>(R' L' U L) // EO + square (4/4)
>
>(D2 F' D' F' ) // 222 (4/8)
>
>(B' U B2) // Pseudo223 (3/11)
>
>R B2 U' B' R U' // 3e (6/17)
>
>Skeleton: R B2 U' B' R U' B2 ? U' B F D F D2 L' U' L R(17)
>
>?: E2 //(1/18) to 4e4x

This shows that FS has no minimum or maximum number of unsolved edges required, apart from the physical limits of the cube obviously.

This first insertion solves one edge, shifts 4 centres and leaves 4 edges unsolved. You can also see this as adding a move to get a new and hopefully better skeleton: 18 moves to 4e4x.

Skeleton: R B2 U' B' R U' B2 D2 U F B D B D2 R' # U' R L // 18 to 4e4x

# : F E2 F' // Solved (4/22)

Often you’ll need a setup to get all 4edges on the same slice. As you can see, slicing back with E2 solves centres and edges with a single slice move.

This example shows the effectiveness of FS also on regular skeletons.

This is a 4 edges FS example by Cale Schoon:

>FS Example 3
>
>Scramble: R' U' F B' D' F' D F2 L2 F2 U' B2 R2 D' R2 U' L R' B D R B U2 R' U' F
>
>(B) U2 F // EO (3/3)
>
>D L (U B2 U2 D2) // Setup to 4c-1e(6/9)
>
>(L' U2 L') // DR trigger (3/12)
>
>U' F2 R2 D R2 // 2e2e (5/17)
>
>Skeleton: U2 F D L U' F2 R2 D R2 L ! U2
>
>L @ D2 U2 B2 U' B'
>
>! = L U M2 U' L' // (6-1/22)
>
>@ = M' E2 M E2 = L' R F2 B2 L' R U2 D2 // (8-6/24)
>
>Solution: U2 F D L U' F2 R2 D R2 L2 U R2 L2 D’ L’ D2 R F2 B2 L’ R B2 U’ B’(24)

Setup Explanation:

D L (U B2 U2 D2) // Setup to 4c-1e(6/9)

*D L – simplifies*

*U B2 – forms semi-bar and E-edge column*

*D2 – forms bar*

*U2 – setups trigger*

This insertion is a bit difficult to see but you can follow along if you sticker your cube. Inserting  the 4 edges in that way leaves 4 centres unsolved. You can insert them at @ with M' E2 M E2 cancelling 6 moves.

Free Slice peaks at multiple edges insertions.

This is a 6e FS example by Guido Dipietro:

>FS Example 4
>
>Scramble:R' U' F L2 D R2 U2 R B' L2 U' L D L2 D L2 D L2 F2 U L2 U F2 R' U' F
>
>(B L' U F D2 B' D2) // 123 block (7/7)
>
>(F2 U' B2) B // 223 (4/11)
>
>R' D' R F D F2 // 6e (6/17)
>
>Skeleton: B R' D' R * F D F2 B2 U F2 D2 B D2 F' U' ** L B'
>
>*: F M2 F' // 6e4x different edges and shifted centres (2/19)
>
>**: M2 // 6e4x to 3e (1/20)
>
>B R' D' R F Rw2 R2 D F2 B2 U F2 D2 $ B D2 F' U' Lw2 L' B' //3edges in 20
>
>$: F L2 B F' D2 B' // (1/21)
>
>Solution: B R' D' R F Rw2 R2 D F2 B2 U F2 D2 F L2 B F2 U' Lw2 L' B' (21)

Solving 6 edges in 4 moves is an incredible achievement.

This is one of my solves (Alexandros Fokianos):

>FS Example 5
>
>Scramble: R' U' F U F2 R2 F2 D L2 U' F2 D2 B2 R' D L2 F' D' L2 R2 U' L2 D B2 R' U' F
>
>U2 D' F // EO (3/3)
>
>L' D' L' (F2 R2 U2) // Setup, 4c-1e case (6/9)
>
>(L U2 L' ) // DR Trigger (3/12)
>
>(U L2 F2 U' R2 D B2 D) // 3e4x in 20
>
>Skeleton: U2 D' F L' D' L' D' F2 * D' L2 U ** B2 R2 U' R U2 R' U2 L2 B2
>
>* S2 (0) // 3e to 4e4x
>
>** M2 (2) // Solved
>
>Solution: U2 D' F L' D' L' D' B2 U' R2 D R2 L2 F2 L2 U' L U2 L' U2 R2 F2 (22)

It wasn’t immediately obvious to me, but there was a 22 moves linear finish after DR:

(U L2 F2 L2 R2 D' R2 U B2 D) // finish in 22

This last example by Sebastiano Tronto (second attempt at WC2019) is a good (and quite  lucky) example of Free Slice insertions.

>FS Example 6
>
>Scramble: R' U' F U2 R2 D' F2 D' L2 U' F2 L F' D' R' U' R2 F L2 B F R2 B2 R' U' F
>
>(B D' R F) // EO + 3 pairs (4/4)
>
>D2 R U' // 2 squares (3/7)
>
>(R2 B2 R) // 3c7e (3/10)
>
>Skeleton: D2 R U' R' B2 R2 [1] F' R' D B' [2]
>
>Insert M2 both at [1] and at [2] to leave 3e3c in 12
>
>New skeleton: D2 R U' R' B2 L2 B' R' U F' * R2 L2
>
>* = U + R U' R2 L2 D R' D' R2 L2 (6)
>
>+ = U2 R' D' R U2 R' D R (6)
>
>Solution: D2 R U’ R’ B2 L2 B’ R’ U F’ U’ R’ D’ R U2 R’ D R2 U’ R2 L2 D R’ D’ (24)

Notice that the edge commutator inserted at * cancels with the M2 inserted at [2]. In fact, one can see the combination of this commutator with the free slice as a 3-move setup to a slice: U R U' M2 U R' U' .

## 5.4 Labor Limae

Some people from the Fewest Moves Facebook group raised the question whether it was possible to improve an already completed solve. And it is! The techniques we know of are: Replace and improve, Slice Insertions and Inserting Algorithms. Most of the times, these can be used because of block building inefficiency. World class FMC solvers usually won’t need them although they may work well for intermediate solvers. The reason why we want to talk about them in this guide is that they are particularly effective when used on DR start solves because of the high number of double and opposite moves.

Always remember that if you don’t have much time to look for a different start, checking whether you can improve your solution can be worth the time investment, even if you are pretty confident about your skills.

### *5.4.1 Replace and Improve*

The idea behind this is very simple: you take a specific part of your solution and replace it with different moves.

You will get a better result if the replacing sequence is shorter or cancels some moves with your solution.

If you manage to do so, it usually means that your block building was not “perfect” and you can try to understand what went wrong in your skeleton.

This is easier said than done though. Understanding which part of the solution can be replaced is not simple.

Some cubers will say things like “that part seemed inefficient” or “it didn’t smell right”. This doesn’t really help.

But a tip that we can give you is: look for parts that look like domino finishes. They are not the only type of sequences this works for, but you have a better chance of succeeding.

Let’s look at an example to see how to do this concretely.

R' U' F R2 B2 L' F2 D2 L' B2 R' B2 U' B2 D' F L U2 L' D U' L F R' U' F

First Solution:

B' D' R2 F' L' R2 U L' B L B' R B (L' B2 R' B2 L R) [D U B2 D' B2 U’ D] (26)

Carefully look at the parts in brackets. They clearly look “domino-ish”.

First, apply L' B2 R' B2 L R to a solved cube. It’s easy to see that R2 U2 R U2 R solves the cube and it’s one move shorter.

Now replace (. . . ) with the inverse of the sequence you found: R' U2 R' U2 R2 Do the same again with D U B2 D' B2 U' D. You should notice that applying L2 D L2 D2 solves the cube. You saved three more moves.

Now replace [. . . ] with the inverse of that sequence: D2 L2 D' L2

If you write down the new solution, it’s 4 moves shorter:

B' D' R2 F' L' R2 U L' B L B' R B R' U2 R' U2 R2 D2 L2 D' L2 (22)

It’s now obvious that Replace and Improve does its best when applied to domino solves. This also means that you shouldn’t worry about always getting the optimal solution because you can fix it afterwards.

The most remarkable example of this technique is the current world record single. In a previous section we were left with a temporary 20 move solution.

R' U' F D2 L2 F R2 U2 R2 B D2 L B2 D' B2 L' R' B D2 B U2 L U2 R' U' F

Temporary solution: D2 F' D2 U2 F' L2 R2 U' D B2 D B2 U B2 F L2 R' F' D U' (20)

Once Sebastiano got this 20 he thought it was not worth looking for a different start. So he tried to use the Replace & Improve technique to find a shorter solution:

Take the sequence in brackets.

Replace U' D B2 D B2 U with R2 D R2 D and you save four moves: two because it’s shorter and two because it cancels. This is what he called, “A 20 minus 4 style points”.

Notice that if you take the sequence R2 U' D B2 D B2 U you could replace it with D R2 D and get the exact same result without the lucky cancellation.

So the final solution is: D2 F' D2 U2 F' L2 D R2 D B2 F L2 R' F' D U' (16)

After the competition, someone else found a DR that only differs from Sebastiano’s by the DR trigger and it’s way simpler! That’s why is important to check any possible trigger after a setup!

(U D' F R) // EO (4/4)

(L2 F' B2) // Setup (3/7)

(D' R2 D' ) // Variation of the DR trigger (3/10)

Can you spot the 6 move ending from here?

Here is a solve Sebastiano showed us in which he successfully replaced a non domino-ish sequence.

R' U' F U2 L' D2 B2 L R F2 R2 D' R2 U' L' D' B2 D2 F' D2 R' U R' U' F

Solution: F R L U' B F2 D' F2 D F2 D2 F2 D R' L D' R D L' D' L' D L D L2 U (26)

But something doesn’t smell right. . . // (see? we told you!)

Scramble: D R' L D' R D L' D'

Solution: B R' D R D' B'

Updated solution: F R L U' B F2 D' F2 D F2 D2 F2 B D R' D' R B' L' D L D L2 U (24)

Much better!

### *5.4.2 Slice insertions*

Same as before, the idea behind this is very simple: you insert a slice somewhere in the solution, leaving 4e4x unsolved, and you slice back somewhere after to solve the 4e4x. We’ll borrow Chong Wen’s explanation for this since it is very clear.

Assuming DR is done on U/D:

“First we find a place with simultaneous U and D moves, because that is the only way we can reduce the solution’s length.

U’ L2 U ** L2 U F2 D2 R2 * D2 U’ B2

Every * is one of them. The next thing to do is to ignore all U and D moves and just look at the “side” moves. If we delete all of them, the string looks like this:

L2 ** L2 F2 R2 * B2

Notice that if you do R2 F2 L2 to get from ** to *, your edges simply do an E move and stay permuted relative to one another, so the E layer is unaffected and you can undo your first slice move there.

So with:

**: E’ // (2-2/0)

*: E // (2-3/-1)

you can shorten your sequence.

Often you get easier cases like: ** F2 L2 L2 F2 * , where the slice is clearly unaffected. Sometimes you can get sequences where you can only ‘transfer’ an E2 across but not an E or E’, like: ** F2 B2 * “. Here are some examples. The first two are from Chong Wen himself, the last ones are from Firstian Fushada. 1 is from a regular skeleton, 2, 3 and 4 are from DR starts.

1) R' U' F D2 R' D2 R2 U2 F2 R' U2 L' U' R' D' R2 B' F' U' L' F' R2 U R' U' F

F' D' R' F2 L R2 F' B' * L2 B R2 B' L2 B F R2 ** F' L B' D2 R' U2 R' F D R' (26)

*=B Bw' (2-3/25)

**=F Fw' (2-2/25)

F' D' R' F2 L R2 F2 z L2 B R2 B' L2 B F R2 Fw' L B' D2 R' U2 R' F D R’ (25)

2) R' U' F D2 F2 L' F2 L' B2 R D2 U2 R2 F2 D' R D' B2 D B' D F U' R' U' F

B2 L F2 B2 R2 D2 L' D R2 D R2 U' R2 U ** R2 B2 F2 U' R2 * U' D' F U' R2 (24)

*=U Uw' (2-3/23)

**=U' Uw (2-2/23)

B2 L F2 B2 R2 D2 L' D R2 D R2 U' R2 D B2 R2 L2 U' B2 D2 F U' R2 (23)

3) R' U' F D B2 U2 L2 F2 U B2 D L R' B D2 R2 F' U R' F' R' U R' U' F

F D R U B R L' D L D' R' F2 U F B L2 F B * D2 U2 R2 D' L2 D R2 ** (25)

* = E2 // 4C4X (2-4/23)

** = E2 // Solved (2-1/24)

F D R U B R L' D L D' R' F2 U B F L2 F B L2 D' R2 U2 D' R2 (24)

4) R' U' F R U R2 B' U2 L2 R2 B' R2 B' U2 B F2 U B' R2 B2 U2 R' U R' U' F

F U2 R' B U2 B2 R2 D U2 R' F2 R U R2 **** U R2 U2 R2 *** U D' R2 * U' D2 F2 D F2 ** U2 (27)

* = E2 (2-3/26)

** = E2 (2-2/26)

*** = E (2-4/24)

**** = E' (2-1/25)

F U2 R' B U2 B2 R2 D U2 R' F2 R U R2 U2 D' F2 U2 F2 R2 U B2 D B2 D2 (25)

Slice insertions can be considered a more general case of Replace and improve.

If the two slices are very close in the skeleton and you take apart the sequence that starts at the first slice and ends at the slice back, you should be able to find the replacement very easily. It’s the same thing, framed in a different way. With slice insertions though, you can insert the first slice at the start of the skeleton and the second one towards the end, giving you more freedom of choice than R&I. It’s not that easy to replace a long sequence, it’s an FMC attempt itself. As you have seen in the examples above, you can also insert multiple slices to cancel more moves, leaving the slice unsolved throughout the skeleton. This is not possible with R&I.

The downside of this technique is that you won’t be able to shorten the non domino-ish sequences, as they don’t depend on slice inefficiency.

The following is Sebastiano’s 16 reframed using slice insertions instead of R&I.

R' U' F D2 L2 F R2 U2 R2 B D2 L B2 D' B2 L' R' B D2 B U2 L U2 R' U' F

Temporary: D2 F' D2 U2 F' L2 R2 U' D * B2 D B2 ** U B2 F L2 R' F' D U' (20)

* : E (2-4/18)

**: E’ (2-2/18)

Solution: D2 F' D2 U2 F' L2 R2 R2 D R2 D B2 F L2 R' F' D U' (18)

Final Solution:D2 F' D2 U2 F' L2 D R2 D B2 F L2 R' F' D U' (16)

### *5.4.3 Inserting algorithms*

There two kinds of algorithms that can be inserted to shorten your solution.

The first ones are the “useless” algorithms, the ones that don’t change the state of the cube after they are applied.

A few examples are:

>M2 E2 M2 E2
>
>M2 S2 M2 S2
>
>E2 S2 E2 S2

The aim is to cancel more moves than the algorithm’s length. In this example, Walker Welch managed to do so:

R' U' F U' F2 L2 D' L2 U' R2 D F2 L2 R' F' U F2 D B U' L2 D' L U R' U' F

L2 U' R U R2 L D2 L' D R' D2 R2 D' L' D R' D' L R' D2 U2 * R2 L' B D U R2 B (28)

*: U2 D2 R2 L2 U2 D2 R2 L2 (8-9/27)

The second kind of algorithms you can insert are commutators. If you see that a sequence in your solution is, for example, an 8 move corner commutator, you can insert its inverse before it to cancel a whopping 8 moves (+8-16), you are basically taking out the 3c comm). Now you are left with a 3c skeleton and all you have to do is find a spot where the commutator cancels at least 1 move. This is very unlikely, but less extreme versions of this can happen.

Say you spot a sequence in your solution that is part of a commutator. If you insert the inverse of the full commutator, cancelling out those moves (e.g. +8-12), you are again left with a 3c skeleton, but this time the insertion has to cancel at least 5 moves to be worth it.

These are obviously very rare occasions so don’t expect to get them very often.

## 5.5 Centers with NISS

Sometimes, when doing CF DR, you will have the need of leaving the centres unsolved. If you also have to use NISS after you have already built some blocks around the wrong centers, you will have some problems when writing down the skeleton. Let’s look at an example. This solve from WC17 had a premade 222 on skew centres.

Sebastiano found this nice skeleton that lead to a 26.

>Centers With Niss
>
>Scramble: R' U' F U R2 B2 D' L2 F2 D U' F2 R' B D' F' U' L R D F2 U F' R' U' F
>
>(U2 L2 B2 U) // 3 pairs (4/4)
>
>R2 D2 R2 // Blocks (3/7)
>
>(L B') // 2x2x3 + square (2/9)
>
>(L2 U2 L' U2 L' U2 L) // All but 3 corners (and centers) (7/16)

The solve is pretty standard up to this point. Now Sebastiano went on to write the skeleton for the inverse scramble.

Skeleton: (U2 L2 B2 U L B' L2 U2 L' U2 L' U2 L B2 L2 B2)

But wait, shouldn’t the last three moves be R2 D2 R2? Think about NISS as a long sequence of moves that doesn’t do anything to the cube. If the centers are shifted you have to imagine inserting the center commutator in-between the moves on the normal scramble and the moves on the inverse scramble. When the moves done on inverse become premoves (to be put at the end of the skeleton), they are done after the centers are corrected.

This obviously works also if you write down the skeleton on inverse, using the moves on the normal scramble as premoves. Our suggestion is to make a small grid with the moves before and after the center insertion. In this case it would be:

>U — B
>
>D — F
>
>F — L
>
>B — R
>
>R — U
>
>L — D

Now all you have to do is “translate” the moves according to the grid. But here comes the tricky part. If you are writing the skeleton for the normal scramble, the grid has to be read left to right: “before — after”. If, as in this case, you are writing the skeleton for the inverse scramble, the grid has to be read right to left: “after — before”.

Going back to the solve, the moves at the end of the skeleton are, in fact, “translated” from R2 D2 R2 to B2 L2 B2. Now you can go on with insertions.
