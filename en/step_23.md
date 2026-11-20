## Add spin sound block

Play a sound as the spin starts.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **dumpling sprite**.



## Step 1

Add the sound block to the start of the script.

```blocks3
when I receive [stars v]
+start sound (Whoop2 v)
repeat (85)
turn cw (15) degrees
end
point in direction (90)
```

## Step 2

Cut the sound off when the spin ends.

```blocks3
repeat (85)
turn cw (15) degrees
end
+stop all sounds
point in direction (90)
```

## Now run your code

Click on the **star**. Check that your sound stops as soon as the dumpling stops spinning.
