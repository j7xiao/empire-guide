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

.. |flank-bonuses| image:: ./images/flank-bonuses.png
    :scale: 50 %
.. |moat-tab| image:: ./images/moat-tab.png
    :scale: 50 %  
.. |inferno-moat| image:: ./images/inferno-moat.png
    :scale: 50 %
.. |castellan-moat-bonus| image:: ./images/castellan-moat-bonus.png
    :scale: 50 %


The wall is divided into three sections: The left flank, the front (flank), and the right flank. Each flank can carry tools which greatly influence the bonuses received on the wall. 

|castle-wall|

:blue:`Overview`
~~~~~~~~~~~~~~~~

There are four strength bonuses on each flank: moat |moat|, ranged |ranged-def|, melee |melee-def|, and wall |wall|. There's also an additional gate bonus |gate| for the front.

You can increse your wall protection by upgrading the physical wall in your castle. For example, a :pink:`level 1` wall grants :olive:`30%` bonus while the :pink:`level 8` wall grants :olive:`200%` bonus.

Likewise, you can increase your gate bonus by upgrading the gate and the moat bonus by upgrading the moat. Simple enough.

:blue:`Calculating Bonsues`
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The overview of a flank will display if you hover or click on its corresponding wall section.
|br| |flank-bonuses|

The symbols should be familiar. From left to right: moat bonus, ranged bonus, melee bonus, and wall bonus. Note, the centre flank will have an additional gate bonus.

:underline:`How are the Numbers Derived?`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's start with the moat bonus, :olive:`254%`.

This castle has a :pink:`level 3` moat (the ruby one for those wondering), which gives :olive:`+70%` bonus. Remember the tool slots I mentioned earlier? Navigate to the moat tab in your castle defense menu. (If you haven't unlocked the moat yet, the moat bonus will display as :olive:`0%` and the tab will be greyed out.)
|br| |moat-tab|

I briefly touched on tool bonuses earlier. Well, each flank can slot one type of moat tool (again, assuming it's actually unlocked). You can stack the tool to :olive:`999`. Unfortunately, this does not mean the tool's effectiveness is increased by a factor of :olive:`999`. Rather, the tool's bonus will be active for :olive:`999` waves of attacks. In other words, every wave of attack against your castle wall consume one tool from each slot.

.. tip::
    It's generally a good idea to keep your tools at :olive:`999` if possible, so their slots aren't left empty after several attacks.

The tool slotted here is listed below. It's tool bonus of :olive:`+110%` is now accounted for.
|br| |inferno-moat|

:underline:`The Castellan Bonus`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

So we have :olive:`+70%` from the physical moat and :olive:`+110%` from the tool slot. We're up to :olive:`+170%`. Fabulous. And where's the remaining :olive:`74%`? The last bonus comes from the castle's castellan. The castellan is an assortment of equipment parts that combine together for powerful bonuses. Let's take a look at this one through the castle defense menu where we have been exploring. (If you have no idea where I am, click your castle gate, then click on Defense from the selection wheel.)
|br| |castellan-moat-bonus|

Found the missing :olive:`+74%`, sir. (:

So to sum up,
:olive:`70% (moat) + 110% (tool) + 74% (castellan) = 254%`.

:underline:`The Other Bonuses`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's revisit this image from earlier:
|br| |castle-wall|

Unlike the moat (and the gate), which have their own dedicated tool slots, the ranged, melee, and wall bonuses all fight for the same tool slots. You'll start with one tool slot for each flank, then gain a slot at wall :pink:`level 2, 3,` and :pink:`5` for :olive:`4` total slots. The :olive:`5th` slot can be specially opened for higher level players who prefer defense over offense, but typically you'll see :olive:`4` slots out in the wild.

The wall and gate, like their moat counterpart, both have innate bonuses from their corresponding building structures. Furthermore, any corresponding tools will additionally boost their stats.

:underline:`Ranged and Melee`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Melee and ranged bonuses have no corresponding building structures. Instead, their defense will always start with 100% base power plus tool and castellan bonuses.

Now's probably a good time to explain what tools are actually being used from this image:
|br| |castle-wall|

:olive:`3` quicklimes bombs (:olive:`+43%` melee bonus each). :olive:`2` balistrarias (:olive:`+70%` ranged bonus each).

And the breakdown of each calculation:

The :blue:`ranged bonus` is comprised of :olive:`100%` base + :olive:`140%` from tools (:olive:`2` "slits" at :olive:`+70%` each) + :olive:`189%` from castellan + :olive:`17%` from sepcial bonuses = :olive:`446%` total ranged power. |br|
The :blue:`melee bonus` is comprised of :olive:`100%` base + :olive:`129%` from tools (:olive:`3` "bombs" at :olive:`+43%` each) + :olive:`194%` from castellan + :olive:`17%` from special bonuses = :olive:`440%` total melee power.

The "special bonuses" are attributed to the Hall of Legends, a :pink:`level 70` building also responsible for unlocking the aforementioned :olive:`5th` tool slot.

You can scroll up and check the ranged and melee bonuses match up with the castellan shown. :3

Now that we have most of the basics down, it's time to dive into actual combat strategies.

.. note::
    And for those of you still wondering how the wall bonus was calculated, it's :olive:`160%` from the wall level and :olive:`186%` from the cast for a toal of :olive:`346%`. There are no tools in any of the slots, so there is no tool bonus.
