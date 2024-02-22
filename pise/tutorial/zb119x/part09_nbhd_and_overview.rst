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

========================
Viewing off-screen nodes
========================


Using the neighborhood view
===========================

Under the "Chart" menu, find "Selection Style," and choose "Node, Edges, Nbrs."
Now once again put your mouse pointer over the overview panel (the thing we opened
in the lower left corner of the screen), so that you see
the two tabs. This time, select the "Neighborhood" tab. You should now see some
colored boxes inside the neighborhood view. (If you don't see them, don't worry,
it just means you need to click
again on the node that says, "$p$ does not divide the discriminant of $k$.")

The boxes in the neighborhood view represent the selected node and its neighbors.
The selected node is in the center, and colored blue. Its *logical antecedents* (nodes
it follows from) are on one side of it and colored purple, and its *logical consequents*
(nodes that follow from it) are on the opposite side and colored green.

Nodes that are (partly or completely) off-screen are dimly colored in
the neighborhood view,
while nodes that are fully on-screen are more brightly colored. If you hover
over the dimly colored box now, you should see a pop-up showing you the
off-screen neighbor of our selected node.
The text size matches that in the main chart area, so if it is too small,
just zoom in (pinch gesture, or :kbd:`Ctrl`-mousewheel) in the main area and try again.

From the pop-up we can see that we are using the premise that $p$ is a prime
distinct from $@ell$. This combines with Theorem 118 to tell us that $p$
does not divide the discriminant of $k$ (hover over Theorem 118 again if you
forgot what it states), which combines with Theorem 31 to
tell us that $p$ factors in $k$ as a product of distinct primes. In other
words, we know that the $frpi@$ are all distinct, and we have completed
one of our three sub-goals in the proof of this theorem.


Using the overview
==================

Let's once again switch back from the neighborhood view to the overview,
by clicking the appropriate tab on the inset panel.
Although it may be hard to see, the boxes here are also colored, according
to your selection in the chart. And here too, if you hover over any off-screen
box, you'll see a pop-up showing the contents of that node. The boxes may be
very small on your screen, but you can do it.
