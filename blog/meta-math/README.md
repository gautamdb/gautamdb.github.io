# Meta-mathematical thoughts

## April 2, 2026

I am quite sure that quite a number of working mathematicians, even in fields which are considered "theoretical", don't have (in the judgement of a logician) a thorough understanding of those parts of mathematical logic which would be relevant as a foundation to what they are doing. These mathematicians rather take a "pragmatic" approach to doing mathematics.

I am one of them. I am one of them who is interested in the foundations of mathematics, though, and in my opinion, understanding these foundations is not a task of mathematical logic alone, but also of philosophic considerations. The foundations of mathematics also lie in philosophy (a subject I am even less knowledgeable about than mathematical logic).

Me with my extremely limited background in these subjects of philosophy of mathematics and mathematical logic, still have my thoughts and views, some of which I would like to share here.

### Constructive mathematics
There is this very interesting book *Constructive Analysis* by Bishop and Bridges, and what becomes clear there is that constructive mathematics takes an approach close to what I would call "numerical implementability": The crux of the matter is that in constructive mathematics, the existence quantifier has a whole new meaning. Understanding this semantic difference is key.

*Existence* in constructive mathematics means that there exists an algorithm to actually construct the object which is posited to exist.

This also explains why the law of the excluded middle in some cases is not valid, or the double negation in some cases doesn't cancel out: Take a statement A, which posits the existence of an object x. Even in constructive math, A and ¬A (*not* A, the negation of A) cannot be true simultaneously. But, for example, a proof by contradiction of ¬¬A (assume that ¬A is true, derive a contradiction, and then conclude that ¬¬A must be true) doesn't prove A in constructive math. Intuitively, because the proof by contradiction does not deliver a way to actually determine the object x, it just gives a reason why it is unthinkable that x doesn't exist.

In contrast, other proofs by contradiciton are as valid in constructive math as outside of it: Suppose the statement A is that an object x *does not* exist. Then assuming that the object *does* exist, and leading this to a contradiction, is a direct proof of the "negative" statement that x does not exist.

As such, constuctive mathematical thoughts can be viewed as a sensible subset of the "classical" (i.e. mainstream) mathematics: Proofs which are constructively valid are still of interest (to an appropriate mathematical audience) even when a non-constructive proof already exists.

### Applying "classical" mathematics requires a certain faith in it
Looking at what constructive math is about lays its finger on the deficit in mathematics as is often perceived by those outside the field: Mathematics seems to live in an abstract world far off from the reality of application.

Take the practical problem of translating mathematical theorems to some numerical application. The theorems might suggest the existence of some specific objects, and when you want to figure out how to let the computer calculate those objects, the theorem is not sufficient: You need to go to the proof and figure out how it was proven that these objects exist. And only when the proof is sufficiently constructive, it is helpful in finding an algorithm. If it is not, further work is required. And one then needs to believe that the theorem is true, even if the proof of the theorem often steps into the realm of double negation arguments, or other arguments involving infinite choices or processes which have no sensible representation in a finite world of computer calculations.

One basically needs to put faith in the idealized world that is the realm of mathematical objects when dealing with them, especially if one wants to believe that those numerical applications which are based on theorems derived very non-constructive methods have any truth value.

### The world of mathematical objects
Take, for instance, a circle drawn on a piece of paper (i.e. in the two-dimensional euclidean plane).

Or, even simpler, consider a point on a piece of paper.

We draw a circle or a point, and we know what we mean, although on the paper, we can never draw a perfect circle or a perfect point. 

A point we draw is a mark on the paper with a positive albeit small area, but what we mean by it is a point with just one position and zero area.

A similar point can be made for the circle.

Mathematical objects and concepts, like the concrete shapes in two-dimensional euclidean space familiar to many, or the more abstract notions of, say, a locally compact Hausdorff topological vector space, live in a space of idealized mathematical thoughts and concepts. 

And this view can be taken from a planonist point of view (this world of mathematical objects exists independent of human minds), or from a naturalistic nominalistic view (if that is the correct nomenclature) - assuming that this world of mathematical thoughts and ideas lives in the shared brain space of us humans, including written texts and the interaction of our brains with these.

### A personal note
I discovered that I might be a strict finitist, and also sympathetic towards constructive mathematics. That the idea of infinite choice, the idea of infinity itself, accpetance of the natural numbers as a completed entity, poses a problem for me. All the more painful is this feeling considering that my PhD topic concerns itself with inherently non-finite dimensional spaces, and the Hahn-Banach Theorem which requires the Axiom of Choice is lurking in many places.

Also, I have discovered that in the long term, I internally need a good reason for doing math which goes beyond "it is fun" - if I feel that it serves no purpose, it poses an obstacle for me.

This has caused some internal upheavals, conflicts, and episodes of long thoughts on philosopical and meta-mathematical questions and considerations. And I think that today, I am coming to a conclusion.

There is this interesting (rather long) monograph called *Strict Finitism and the Logic of Mathematical Applications*. (I admit to have only read the first chapter and skimmed the first half of the second chapter.) It offers a perspective on how the applicability of abstract "infinite" math to the finite tools of computation, which we use to comprehend and measure the world around us, might be answered within the philosophy of math and with mathematical logic.

All in all, taking a leap of faith, I can carry on doing mathematics in the realm of constructive *and* non-constructive arguments, without worrying my mind that it might be pointless.

So, was it all a waste of time, bothering my mind so much with these thoughts? I think and hope not. Besides the fact that it was in some sense inevitable, it will probably influence what topics I choose to work on in future.
