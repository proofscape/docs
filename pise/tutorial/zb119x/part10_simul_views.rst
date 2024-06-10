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

==================
Simultaneous views
==================

This section covers some advanced use of the visualization capabilities of PISE.


Controlling the inset panel
===========================

If you right-click the inset panel, you'll see a context menu. You see that you
can move the panel to any of the four corners, or even close it altogether.
(All this can also be done from the Chart menu.)

If you uncheck the "AutoView" option, then you can pan and zoom within the
inset panel itself. Check "AutoView" again to make the view automatically
track what's visible in the main diagram area.


A "mid-sized" overview
======================

If the overview panel seems a bit too small, there is always another way to have
simultaneous views of the diagram.

At the top of the diagram panel, you should see a tab, with a "navigation" or
"ship's wheel" icon. Right-click the tab, and look for "Open in Opposite Group."
If you click that, you're going to cover up these notes, and I'll ask you to please
come back after you've finished looking around.

While you're there, you may notice
that the highlight colors in the two views are linked (try clicking a few different
nodes in each tab). By zooming out in one view, you can have a kind
of "mid-sized overview panel."


Ordered layout
==============

Another thing you might try while you have two chart tabs open is to change
the layout in the new tab (again, that's Chart Menu ``->`` Layout) to "OrderedList"
layout. Note that the "Chart" menu always controls the *active* chart tab, i.e.
the last one you clicked or interacted with in any way.

OrderedList layout presents the nodes in linear order, as they might appear in a
prose proof. Since, again, highlight colors in the two tabs are linked, this can provide
a nice counterpoint, and can help guide you through the flow chart in a sensible order.


Multiple windows
================

Between these notes, and now two chart views (and maybe even some source modules?)
the ISE may be starting to feel a bit crowded, even though you can open as many
splits (vertical or horizontal) as you wish (see the context menus on the tabs at the
top of the panels).

Luckily, if you have multiple computer monitors, you can actually
use all of that space. Again right-clicking the tab for one of the chart views,
you should see a grayed-out option to "Move to window...". If you load the Proofscape
ISE in a second browser window -- i.e. another completely separate window of your web
browser -- this option will become enabled, and you can move a tab over to the other
window. If you put the second window on your second monitor, you can really take advantage
of all that screen space.

If you try this, you'll find that the two chart
tabs will still be linked, and share highlight colors. Moreover, the chart panel
that is controlled by the widgets in these notes will continue to be controlled
by them, even if you move it to the other window.
