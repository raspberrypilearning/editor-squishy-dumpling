## Add a spinning sound

Play a sound for as long as the spin lasts.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **Dumpling sprite**.

## Step 1

Add a `start sound`{:class="block3sound"} block to the top of the spin script and choose a sound.

```blocks3
when I receive [stars v]
+start sound (Whoop2 v)
repeat (85)
turn cw (15) degrees
end
point in direction (90)
```

## Step 2

Cut the sound off when the spin ends with a `stop all sounds`{:class="block3sound"} block.

```blocks3
repeat (85)
turn cw (15) degrees
end
+stop all sounds
point in direction (90)
```

## Now run your code

Click on the **Starfish**.

Check that your sound stops as soon as the dumpling stops spinning.
