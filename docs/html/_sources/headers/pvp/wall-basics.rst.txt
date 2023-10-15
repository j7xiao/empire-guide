Wall Basics
===========

.. |castle-wall| image:: ./images/castle-wall.png
    :scale: 50 %

.. |gate| image:: ./images/gate.png
    :scale: 50 %
.. |melee-def| image:: ./images/melee-def.png
    :scale: 50 %
.. |moat| image:: ./images/moat.png
    :scale: 50 %
.. |ranged-def| image:: ./images/ranged-def.png
    :scale: 50 %   
.. |wall| image:: ./images/wall.png
    :scale: 50 %

.. |lv1-wall| image:: ./images/lv1-wall.png
    :scale: 40 %
.. |lv8-wall| image:: ./images/lv8-wall.png
    :scale: 40 %

.. |flank-bonuses| image:: ./images/flank-bonuses.png
    :scale: 50 %
.. |moat-tab| image:: ./images/moat-tab.png
    :scale: 50 %  
.. |inferno-moat| image:: ./images/inferno-moat.png
    :scale: 50 %
.. |castellan-moat-bonus| image:: ./images/castellan-moat-bonus.png
    :scale: 50 %


The wall is divided into three sections: The left flank, the front, and the right flank. Each flank (including the front) can carry tools which greatly influence the bonuses received on the wall. 

|castle-wall|

:blue:`Overview`
~~~~~~~~~~~~~~~~

There are four strength bonuses on each flank: moat |moat|, ranged |ranged-def|, melee |melee-def|, and wall |wall|. There's also an additional gate bonus |gate| for the front.

You can increse your wall protection by upgrading the wall in your castle. For example compare a :pink:`level 1` wall (:olive:`30%` bonus) against a :pink:`level 8` wall (:olive:`200%` bonus):

|lv1-wall| |lv8-wall|

Likewise, you can increase your gate bonus by upgrading the gate and the moat bonus by upgrading the moat. Simple enough.

:blue:`Calculating Bonsues`
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The overview of a flank will display if you hover or click on its corresponding wall section.
|br| |flank-bonuses|

The symbols should be familiar. From left to right: moat bonus, ranged bonus, melee bonus, and wall bonus. Note, the centre flank will also have a gate bonus.

:underline:`How are the Numbers Derived?`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's start with the moat bonus, :olive:`254%`.

This castle has a :pink:`level 3` moat (the ruby one for those wondering), which gives :olive:`+70%` bonus. Remember the tool slots I mentioned earlier. Navigate to the moat tab in your castle defense menu. (If you haven't unlocked the moat yet, the moat bonus is :olive:`0%` and the tab will be greyed out.)
|br| |moat-tab|

I briefly touched on tool bonuses earlier. Well, each flank can slot one type of moat tool (again, assuming it's actually unlocked). You can stack the tool to :olive:`999`. Unfortunately, this does not mean the tool's effectiveness is multiplied by :olive:`999`. Rather, the tool's bonus will be active for :olive:`999` waves of attacks. In other words, every wave of attack against your castle wall consume one tool from each slot.

.. tip::
    It's generally a good idea to keep your tools at 999 if possible, so their slots aren't left empty after several attacks.

The tool slotted here is listed below. It's tool bonus of :olive:`+110%` is now accounted for.
|br| |inferno-moat|

:underline:`The Castellan Bonus`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

So where's the rest of the :olive:`254%`? The last bonus comes from the castle's castellan. The castellan is an assortment of equipment parts that combine together for powerful bonuses. Let's take a look at mine through the castle defense menu where we have been exploring. (If you have no idea where I am, click your castle gate, then click on Defense from the selection wheel.)
|br| |castellan-moat-bonus|

There's the remaining :olive:`+74%`. (:

:olive:`70 + 110 + 74 = 254.`

:underline:`The Other Bonuses`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's revisit this image from earlier:
|br| |castle-wall|

Unlike the moat (and the gate), which have their own dedicated tool slots, the ranged, melee, and wall bonuses all fight for the same tool slots. You'll start with one tool slot for each flank, then gain a slot at wall :pink:`level 2, 3,` and :pink:`5` for :olive:`4` total slots. The :olive:`5th` slot can be specially opened for higher level players who prefer defense over offense, but typically you'll see :olive:`4` slots out in the wild.

The wall and gate, like their moat counterpart, both have innate bonuses from their corresponding building structures. Furthermore, any corresponding tools will additionally boost their stats.

:underline:`Ranged and Melee`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Melee and ranged bonuses have no corresponding building structures. Instead, their defense will always start with 100% base power plus tool and castellan bonuses.

Referring to the flank overview image from `Calculating Bonsues`_ and the castellan image from `The Castellan Bonus`_ again, we can determine that: 

The :blue:`ranged bonus` is comprised of :olive:`100%` base + :olive:`140%` from tools (:olive:`2` "slits" at :olive:`+70%` each) + :olive:`189%` from castellan + :olive:`17%` from sepcial bonuses = :olive:`446%` total ranged power. |br|
The :blue:`melee bonus` is comprised of :olive:`100%` base + :olive:`129%` from tools (:olive:`3` "bombs" at :olive:`+43%` each) + :olive:`194%` from castellan + :olive:`17%` from special bonuses = :olive:`440%` total melee power.

The "special bonuses" are attributed to the Hall of Legends, a :pink:`level 70` building responsible for unlocking the aforementioned :olive:`5th` tool slot.

Now that we have most of the basics down, it's time to dive into actual combat strategies.

.. note::
    And for those of you still wondering how the wall bonus was totalled, it's :olive:`160%` from the wall level and :olive:`186%` for a toal of :olive:`346%`. There are no tools in any of the slots, so there is no tool bonus.
