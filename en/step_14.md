## Face the front again

Finish the spin facing forwards, so the dumpling is never left on its side.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **dumpling sprite**.

Point the dumpling the right way up when the spin ends.

```blocks3
when I receive [stars v]
repeat (85)
turn cw (15) degrees
end
+point in direction (90)
```

## Now run your code

Click on the **star**. Check that the dumpling is upright at the end of the spin.

![The dumpling ends the spin upright.](images/step-14.gif){:width="450px"}
