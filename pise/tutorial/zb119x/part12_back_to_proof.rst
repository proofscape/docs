.. ............................................................................
   : Copyright (c) 2018-2024 Proofscape Contributors                          :
   :                                                                          :
   : This Source Code Form is subject to the terms of the Mozilla Public      :
   : License, v. 2.0. If a copy of the MPL was not distributed with this      :
   : file, You can obtain one at http://mozilla.org/MPL/2.0/.                 :
.. ...........................................................................:

.. pfsc::

    import gh.toepproj.lit.H.ilbert.ZB.Thm119 as Thm119

.. pfsc-ctl::
    :default_chart_group: ".."

======================================
Back to the proof! Next Goal: $e' = e$
======================================

Okay, we took another detour to learn about features of the Proofscape ISE, but
now it's time to get back to the proof.
If you opened new tabs (or even new windows) in the last couple of sections,
please close them now, and come back to just these notes and the original
chart panel. (If you lost the original chart panel, don't worry: when you click
the next widget, you'll be back in business.)

En route to |w44: the conclusion of the theorem|,
we said we had three sub-goals to prove
regarding the way the rational prime $p$ factors in the cyclotomic field $k$, and we
established
:pfsc-chart:`w45: the first of these <Thm119.Pf.A190>`, i.e. that the factorization
is squarefree.

.. |w44: the conclusion of the theorem| pfsc-chart::
    :onBoard: Thm119.Pf
    :view: Thm119.Thm.A


With this knowledge in hand, we write the factorization of $p$
into prime ideals like |w49: this|, introducing $e'$ as the number of distinct ideals.
Our :pfsc-chart:`w54: goal <Thm119.Pf.A240>` now is to show that this is equal to
the $e$ that we defined in the theorem statment.

.. |w49: this| pfsc-chart::
    :view: Thm119.Pf.I200
    :select: null
    :color: "olB: Thm119.Pf.I200"

Remember that the selected node is highlighted in blue, while its logical antecedents
are purple, and its consequents green.

Also remember that you now know several ways
to review the node where $e$ was defined if it is currently off-screen.
Hint: use the overview or neighborhood panels! Also remember that you can move
the inset panel to any of the four corners if it is in the way: use the Chart menu,
or right-click the panel itself.

By the way, as we proceed I encourage you to continue checking the goal boxes
in the upper-right corners of the nodes. (If you missed this, go back and read
:doc:`part11_keeping_track`.) For a node that merely introduces new symbols, like
|w59: this one|, it makes sense to check the box as soon
as you've read and understood what the node says. This one, then, can be checked
right now.

.. |w59: this one| pfsc-chart::
    :view: Thm119.Pf.I200
    :select: null
    :color: "olB: Thm119.Pf.I200"

For a node that draws a conclusion, like
:pfsc-chart:`w60: our current goal <Thm119.Pf.A240>`, it makes sense to wait until
you've reached the point in the argument where you see that this conclusion does
indeed follow. This time the checkmark means, "I am convinced that this step is
valid." For now, this one will have to wait.
