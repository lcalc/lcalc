# lcalc

`lcalc.tgz' contains the formalization of the L_beta-calculus
and the proof of its Church-Rosser property written in Minlog.

This is the proof that corresponds to the proof of Theorem 38
(Church-Rosser) of our `Unification ...' paper.  The constructors Var
and Prj in the proof corresponds to the alpha canonical threads as
below (u and v are seq of fresh binders and 1 is a canonical
variable).

Var i x   ....   [u]x      where |u|=i
Prj i k   ....   [u1v]1    where |u|=i, |v|=k
