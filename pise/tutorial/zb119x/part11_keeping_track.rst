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

=========================
Keeping Track of Progress
=========================

PISE is part project planner. Tackling a big proof can be, after all, a big
project. You could spend a day or even a week understanding just one section.
Then another week on another section. Then, after all that time, you'll need
to zoom back out and remember how those separate sections fit into the big picture.

Moreover, as you work your way through a proof, you need a way to keep track of
your progress. Which parts have you understood so far? Were there difficulties
you wanted to return to later? Where should you go next?
For all this, PISE provides *Goal Boxes*, and *Study Pages*.


Goal Boxes
==========

Now is a good time to start using goal boxes. You should see a small box
in the upper-right corner of each node in the diagram. (If not, go to the
Study menu and make sure the "Show Goal Boxes" option is checked.)

By clicking these boxes, you can toggle checkmarks on and off, and this is
a good way to keep track of which nodes you have already examined and understood
in the proof. Go ahead and check the boxes for
:pfsc-chart:`w55: these two nodes <"Thm119.Pf.{A180,A190}">` now.
This represents our progress so far, in understanding this proof.

Under default settings, the state of these checkboxes will be stored in your
browser at least until you
close the browser tab where you are currently working. If you want them to be
more permanent, you can try activating the different options under the
Study menu, to "Record Notes in Browser" or (if it is enabled) "Record Notes on
Server". When you select these options, dialog boxes will come up to give you
more information about how they work. You can also use the Study menu to export
your checkmarks in JSON format, and then import them again later.

.. note::

    If you're `running PISE on your own computer`_, using the PISE Docker image,
    then the option to record notes on the server is always selected.
    In this case, the server is running on your own machine, so recording your notes
    this way just means saving them on your computer's hard drive. If, on the contrary,
    you are reading this tutorial on an online server, it may or may not be configured
    to offer you the option to record your notes there. If it does offer the option,
    you have to log in first, and then opt-in by checking the box in the Study menu.


.. _running PISE on your own computer: https://docs.proofscape.org/pise/basic.html


Jotting Down Notes
==================

Goal boxes also give you a way to jot down notes. Find the goal box for the
|w56: conclusion node|, and right-click *the goal box (not the node)*.
You should see a context menu.
If you select the "Notes" option on this menu,
you'll see a dialog box, where you can record any notes you
wish, in Markdown syntax.
You write your notes under the "Edit" tab.
For example, you might write something like this:


.. code-block::

    Have three things to show:

    * the prime ideals $\mathfrak{p}_i$ are all distinct
    * there are $e$ of them
    * each has degree $f$


Go ahead and try that now.
Then you can click the "Notes" tab, to see your notes rendered.

Your notes will be stored in the same way as your checkmarks, according to the
options you have activated under the Study menu (see above).

.. |w56: conclusion node| pfsc-chart::
    :view: Thm119.Thm.A
    :color: "bgY: Thm119.Thm.A"


Study Pages
===========

As you accumulate notes and checkmarks, you may wish to see a summary of what
you've recorded so far.
For that, right-click on the *node* (not the goal box)
for which you just recorded some notes, and select the option to
"Open study page."

In a moment you should see an automatically generated page including all the
goals for the theorem (not the proof), including the notes you just wrote.
Similarly, you can open the study page for the *proof* by right-clicking any
of its nodes, and again choosing "Open study page". There you will see reflected
the checkmarks you recorded earlier.

If you right-click the tab for the study page, and select
"Move to Opposite Group," you'll be able to see both the study page and the
proof chart at the same time. If you try checking/unchecking some of the goal
boxes in the study page, you'll see that they are linked to the corresponding
boxes in the diagram. You may also notice that each goal listed in the study
page is clickable, and will navigate you through a copy of the proof diagram.

It should now be clear how, as you accumulate
notes and checkmarks, these study pages can provide you with a nice report of
what you've thought about so far, and what progress you've made in studying
proofs.

When you're done checking out your study pages, close them, come back to the
chart tab, and we'll resume with our study of the proof.
