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

=================
Opening the Proof
=================

Now we can open the proof. You can always do this by finding
:pfsc-chart:`w24: a node that needs proof <"Thm119.Thm.A">` -- in this case the node
that makes the assertion of the theorem -- then *right-click* this node, and look
for an *Expansion*. You can try it yourself now, or I can
:pfsc-chart:`w25: open the proof <"Thm119.Pf">` for you.

After the proof opens, you may find that the text on the nodes has become
too small to read.
If you have a multitouch trackpad, you can pan with scrolling gestures in both
dimensions, and zoom with the pinch gesture. If you are
using a mouse, you can pan by clicking and dragging, and zoom by holding
:kbd:`Ctrl` while using the mouse wheel.

Now we need to get our bearings. If you were watching closely during the animation
in which the proof opened, you may have observed that the theorem was
*expanded* to make room for the proof. The premises of the theorem went to one
side of the diagram, and the conclusion to the opposite side.

Let's locate the nodes of the theorem now.
The premises are
:pfsc-chart:`w26: here <"Thm119.Thm.{I1,I2,I3}">`, and the
conclusion is :pfsc-chart:`w27: here <"Thm119.Thm.A">`.
If you clicked the last two widgets you should have seen the diagram pan
and zoom to display the nodes I'm talking about.
