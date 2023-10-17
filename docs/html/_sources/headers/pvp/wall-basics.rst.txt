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

You can increse your wall protection by upgrading the physical wall in your castle. For example, a level :number:`1` wall grants :number:`30%` bonus while the level :number:`8` wall grants :number:`200%` bonus.

Likewise, you can increase your gate bonus by upgrading the gate and the moat bonus by upgrading the moat. Simple enough.

:blue:`Calculating Bonsues`
~~~~~~~~~~~~~~~~~~~~~~~~~~~

The overview of a flank will display if you hover or click on its corresponding wall section.
|br| |flank-bonuses|

The symbols should be familiar. From left to right: moat bonus, ranged bonus, melee bonus, and wall bonus. Note, the centre flank will have an additional gate bonus.

:underline:`How are the Numbers Derived?`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's start with the moat bonus, :number:`254%`.

This castle has a level :number:`3` moat (the ruby one for those wondering), which gives :number:`+70%` bonus. Remember the tool slots I mentioned earlier? Navigate to the moat tab in your castle defense menu. (If you haven't unlocked the moat yet, the moat bonus will display as :number:`0%` and the tab will be greyed out.)
|br| |moat-tab|

I briefly touched on tool bonuses earlier. Well, each flank can slot one type of moat tool (again, assuming it's actually unlocked). You can stack the tool to :number:`999`. Unfortunately, this does not mean the tool's effectiveness is increased by a factor of :number:`999`. Rather, the tool's bonus will be active for :number:`999` waves of attacks. In other words, every wave of attack against your castle wall consume one tool from each slot.

.. tip::
    It's generally a good idea to keep your tools at :number:`999` if possible, so their slots aren't left empty after several attacks.

The tool slotted here is listed below. It's tool bonus of :number:`+110%` is now accounted for.
|br| |inferno-moat|

:underline:`The Castellan Bonus`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

So we have :number:`+70%` from the physical moat and :number:`+110%` from the tool slot. We're up to :number:`+170%`. Fabulous. And where's the remaining :number:`74%`? The last bonus comes from the castle's castellan. The castellan is an assortment of equipment parts that combine together for powerful bonuses. Let's take a look at this one through the castle defense menu where we have been exploring. (If you have no idea where I am, click your castle gate, then click on Defense from the selection wheel.)
|br| |castellan-moat-bonus|

Found the missing :number:`+74%`, sir. (:

So to sum up,
:number:`70% (moat) + 110% (tool) + 74% (castellan) = 254%`.

:underline:`The Other Bonuses`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's revisit this image from earlier:
|br| |castle-wall|

Unlike the moat (and the gate), which have their own dedicated tool slots, the ranged, melee, and wall bonuses all fight for the same tool slots. You'll start with one tool slot for each flank, then gain a slot at wall level  :number:`2`, :number:`3`, and :number:`5` for :number:`4` total slots. The :number:`5th` slot can be specially opened for higher level players who prefer defense over offense, but typically you'll see :number:`4` slots out in the wild.

The wall and gate, like their moat counterpart, both have innate bonuses from their corresponding building structures. Furthermore, any corresponding tools will additionally boost their stats.

:underline:`Ranged and Melee`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Melee and ranged bonuses have no corresponding building structures. Instead, their defense will always start with 100% base power plus tool and castellan bonuses.

Now's probably a good time to explain what tools are actually being used from this image:
|br| |castle-wall|

:number:`3` quicklimes bombs (:number:`+43%` melee bonus each). :number:`2` balistrarias (:number:`+70%` ranged bonus each).

And the breakdown of each calculation:

The :blue:`ranged bonus` is comprised of :number:`100%` base + :number:`140%` from tools (:number:`2` "slits" at :number:`+70%` each) + :number:`189%` from castellan + :number:`17%` from sepcial bonuses = :number:`446%` total ranged power. |br|
The :blue:`melee bonus` is comprised of :number:`100%` base + :number:`129%` from tools (:number:`3` "bombs" at :number:`+43%` each) + :number:`194%` from castellan + :number:`17%` from special bonuses = :number:`440%` total melee power.

The "special bonuses" are attributed to the Hall of Legends, a level :number:`70` building also responsible for unlocking the aforementioned :number:`5th` tool slot.

You can scroll up and check if the ranged and melee bonuses match up with the castellan shown. :3

Now that we have most of the basics down, it's time to dive into actual combat strategies.

.. note::
    And for those of you still wondering how the wall bonus was calculated, it's :number:`160%` from the wall level and :number:`186%` from the cast for a toal of :number:`346%`. There are no tools in any of the slots, so there is no tool bonus.
