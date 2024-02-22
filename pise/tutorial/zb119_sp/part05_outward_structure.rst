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

===========================
Outward Structure the Proof
===========================

Before we even get into the mathematics of the proof,
let's return to :pfsc-chart:`w39: the bird's eye view <"Thm119.{Thm,Pf}">`.
(By the way, you can always double-click anywhere on the *background* of the
chart area to make all nodes visible.)

From here we can spy what may turn out to be meaningful structures within the
proof. (At this point, these are just guesses.)

On one side of the diagram there appears to be |w40: a small cluster| of nodes.

.. |w40: a small cluster| pfsc-chart::
    :color: "olB,bgB: Thm119.Pf.{A190,Thm31,A180,Thm118}"

Looking more closely, we might observe that certain nodes form
|w41: a kind of loop|, into which |w42: these nodes| seem to feed.

.. |w41: a kind of loop| pfsc-chart::
    :color: "olB,bgB,eoB: Thm119.Pf.{I80,R90,A100,A110,A120,A140,A150,A160}"

.. |w42: these nodes| pfsc-chart::
    :color: "olB,bgB,eoB: Thm119.Pf.{I60,Thm24,A95,Thm26,A70,A50,A40,I30,S20,I10,S130}"

Selecting |w43: the three premises| and tracing their outgoing connections,
we see where they feed into the picture.
(You can also try clicking on them one at a time, to highlight them individually.)
Selecting |w46: the conclusion|, we see that it drops out of |w1: another small cluster|,
which itself draws together the "loop" and the first small cluster we identified earlier.

.. |w43: the three premises| pfsc-chart::
    :color: "olB,bgB,eoBG: Thm119.Thm.{I1,I2,I3}"

.. |w46: the conclusion| pfsc-chart::
    :color: "olB,bgB,eiVB: Thm119.Thm.A"

.. |w1: another small cluster| pfsc-chart::
    :color: "olB,bgB: Thm119.Pf.{A240,A230,A220,A170,I200,A210}"
