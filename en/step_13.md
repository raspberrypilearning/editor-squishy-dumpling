## Face the front again

Finish the spin facing forwards, so the dumpling is never left on its side.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **Dumpling sprite**.

Add a `point in direction`{:class="block3motion"} block under the loop.

```blocks3
when I receive [stars v]
repeat (85)
turn cw (15) degrees
end
+point in direction (90)
```

## Now run your code

Click on the **Starfish**.

Check that the dumpling is upright at the end of the spin.
