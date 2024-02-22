..
  # ------------------------------------------------------------------------- #
  # Proofscape Doc Modules                                                    #
  # Copyright (c) 2018-2024 Proofscape contributors                           #
  #                                                                           #
  # This Source Code Form is subject to the terms of the Mozilla Public       #
  # License, v. 2.0. If a copy of the MPL was not distributed with this       #
  # file, You can obtain one at http://mozilla.org/MPL/2.0/.                  #
  # ------------------------------------------------------------------------- #

.. pfsc::

    import gh.toepproj.lit.H.ilbert.ZB.Thm119 as Thm119

.. pfsc-ctl::
    :default_chart_group: ".."

======================
Delving into the Proof
======================

Okay, it's finally time to get down to the business of examining the argument,
but I will continue to teach you how to use the software as we go.

So... We want to show that $p$ factors in $@k = bbQ(zeta)$ like |w52: this|.
This includes the fact that...

* the prime ideals $@frpi$ dividing $p$ are distinct,
* there are $e$ of them, and
* each is of degree $f$.

.. |w52: this| pfsc-chart::
    :view: Thm119.Thm.A
    :color: "bgY: Thm119.Thm.A"
    :select: null

Let's begin with the fact that the $frpi@$ are all distinct, i.e. that $p$ is
squarefree, or unramified in $k$.
If we had been studying the *Zahlbericht* text up to this point, it would be
fresh in our minds that a prime is unramified in a number
field just in case it does not divide the discriminant of the field. And so
it would be reasonable to begin this proof by bringing these facts to bear,
and this is what happens right |w53: here|.

.. |w53: here| pfsc-chart::
    :color: "bgY: Thm119.Pf.{Thm118,A180,A190,Thm31}"
    :view: "Thm119.Pf.{Thm118,A180,A190,Thm31}"

If you hover your mouse pointer over the nodes for Theorems 31 and 118, you
will see pop-ups showing the theorem statements. The theorems can also be
opened by double-clicking, but it's best if we save that for later. (If you
do open them, remember that you can close them using their right-click
context menu.)

Now click on the node that says, "$p$ does not divide the discriminant of $k$."
We can see that this node is connected to three others, but one of its
connectors probably runs off screen (unless you have a giant monitor). We can of
course pan the view in order to find the off-screen neighbor, but there is another
way, which we review next.
