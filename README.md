TextGlowDemo
============

iPhone OS’s UILabel provides basic shadowing properties which can be used to create inset text effects and basic text shadows. However, the shadow has no blur and gives a sharp edge which is not particularly useful if you’re looking for a soft or subtle shadow.

Recently I needed to create a “glowing” text effect – essentially a soft shadow without the offset – so I wrote a simple UILabel subclass which let me specify an offset, colour and blur amount.



The screenshot shows a how the class can be used to create a glow effect but it’s equally easy to create soft shadows for your text.
