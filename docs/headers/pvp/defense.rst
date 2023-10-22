The Art of the ... Defense?
===========================

.. |castle-wall| image:: ./images/castle-wall.png
    :scale: 50 %

We already introduced the defense under `wall basics <introduction.html>`_. Give it a read if you haven't already. No, go ahead. I'll wait. (:

:blue:`The Castle Wall -- Revisted`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|castle-wall|

The left flank says :number:`98%`, the front :number:`1%`, and the right flank :number:`1%`. This is called your wall ratio. The above wall ratio would be designated as ":number:`98-1-1`" in shorthand. You can adjust it by sliding the wooden knobs around. The :number:`6,793` on the right tab indicates how many troops the wall can hold ("wall unit capacity"). The :number:`0/6,793` means that there are zero troops in the castle.

This is actually an important topic that is worth sidetracking a moment for.

.. important::
    Troops are an extremely valuable asset. Until very late game, they are extremely succeptible to enemy attacks. There will always be a bigger fish, meaning your troops are never safe. While you are away from the game, it is important to safehouse your troops, by stationing them at an alliance mate who is under protection mode. Protection mode prevents another player from attacking them, but in exchange, they can't hit other players. All larger alliances will have a "bird" to send troops to when you're away from the game - Even if it is a shell account whose only purpose is to safehouse troops. That's how important it is. You'll even see top players bird their troops!

Anyways, back to the wall ratio. Why are almost all of the troops grouped on one flank? This is due to how the castle wall battle functions. The attackers has :number:`3` flanks to attack from, just like the defender has :number:`3` flanks to defend from.

:blue:`Basic Battle Mechanics`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There are two parts of the attack: the wall battle and the courtyard assault. Most attack troops are typically in the wall battle, but there will be trailing troops called the "courtyard assault". If the attacker manages to break at least one flank, all surviving troops in addition to the courtyard assult will fight in the ensuing courtyard battle. The courtyard assault will be returned to the attacker if all :number:`3` flanks are successfully defended.

If the defender sucessfully defends :number:`2` flanks, he gains a :number:`30%` courtyard strength bonus. If the defender only defends :number:`1` flank, the courtyard battle "goes even", and neither side receives a bonus. If the defender cannot defend any flank, then the attackers gains a :number:`30%` courtyard strength bonus.

Typically, a player can comfortably defend one flank. There are some situations, where the defender may elect to defend two flanks (:number:`35-65-0` or :number:`50-0-50` typically). There is an inherent risk. If he sucessfully defends two flanks, he gets the :number:`30%` courtyard bonus. But usually if he can't, he loses both flanks and the attackers gains :number:`30%` courtyard bonus. That is a massive swing in power, and can make or break an attack.

:blue:`The Melee/Ranged ratio`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. |m-r-ratio| image:: ./images/m-r-ratio.png
    :scale: 50 %

Let's borrow this image yet again:
|castle-wall|

The quiver and sword image on each flank determines the melee/range ratio of the wall segment. Click on it to reveal the ratio of troops on that wall section. This is called the m/r ratio. A lot of experienced players will write it in shorthand. The below image for example is :number:`80%` melee and :number:`20%` ranged or ":number:`80m/20`" in shorthand.
|br| |m-r-ratio|

Assuming there is enough troops to fill the wall up with the correct ratio, the game will first partition the wall up (in this case, :number:`98-1-1`). Then the game will populate the wall up to the wall unit capacity according to the m/r ratio of each section. All other troops in the castle will be kept in the courtyard pending a potential courtyard battle.

:blue:`Why 80m/20?`
~~~~~~~~~~~~~~~~~~~

If you're reading on from the `previous section <tools-waves.html>`_, this is the part you have been waiting so patiently for. Here we'll explain what influences the m/r ratio. This will ultimately determines how you'll setup your attack.

Remember how I explained there were two types of waves, the "shield wave" and the "alt wave"? Its necessity is based off optimal defense setups. Let's explore how the attacker can overcome common defense setup blunders.

:underline:`1. 100r/0 ~ A Lesson in Wall Wiping`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Remember how the melee and ranged bonus starts with :number:`100%` power? If the attacker reduces the ranged bonus below :number:`100%` with shield walls, the ranged defenders effectively operate at partial power. But what if the attacker reduces the ranged power to :number:`0%`?

This is what wall wiping is. It doesn't matter if there are 200 or 200 million ranged troops on the wall. If the ranged power is reduced to :number:`0%`, functionally speaking, their collective power is :number:`0`. This makes sense as their power is being multiplied by :number:`0.` This means if the attacker sends at least 1 troop, that 1 troop will kill the entire wall section, hence "wiping" (again, assuming it's all ranged). 

The absolute maximum ranged bonus on the wall is :number:`100%` (base) + :number:`250%` (:number:`5` slits) + :number:`300%` (maximum castellan) = :number:`650%`. If you sent :number:`44` shield walls, that will bring the defenders ranged bonus to :number:`-660%`. Although on that note, the ranged bonus cannot be reduced below :number:`0%`. There are no mechanics for "healing" your own troops in battle.

.. danger::
    Do not set your wall ratio to all ranged! 100r/0 would bring even the strongest player down to their knees.

:underline:`2. 100m/0`
^^^^^^^^^^^^^^^^^^^^^^

Thankfully, the attacker cannot reduce the melee defender's power, so you can avoid the wall wiping fiasco. However, :number:`100m/0` is still a blunder. The attacker sends all ranged. The attacker gets type advantage for free. The attacker does not need to send shield waves, which means all his waves are sent at :number:`100%` strength as there are no tools being "`left out <tools-basics.html#three-defensive-bonuses-two-tool-slots-help>`_".

:underline:`3. Ranged Majority`
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Remember that the defending ranged troop's power can be reduced by attacking tools. That is why it is a mistake to set your ratio to ranged majority. If you set to :number:`70r/30` for example, the attacker can compose his attack of majority shield waves, and nullify :number:`70%` of your troop power!

:blue:`Melee Majority Ratio`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

So what we have left is melee majority ratio. So Why :number:`80m/20`? The answer is that it provides enough unreduceable melee power while also providing ranged power to interfere with any attacking ranged troops, as again, :number:`100m/0` is a blunder. Some people will argue for :number:`70m/30`. This is a valid argument as well, but depends on how many shield waves the attacker sends. We must swap back to the attacking aspect before completing our journey through the Art of the Attack.

You're almost done! ヾ（〃＾∇＾）ﾉ♪
