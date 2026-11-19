## Change colour

Flash the dumpling through lots of colours.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 1

Click on the **Dumpling sprite**.

Add a `when I receive`{:class="block3events"} block set to `rainbow`{:class="block3events"}, and a `repeat`{:class="block3control"} loop with a `change effect by`{:class="block3looks"} block inside.

```blocks3
+when I receive [rainbow v]
+repeat (15)
+change [color v] effect by (pick random (20) to (30))
+end
```

## Step 2

Slow the colour change down with a `wait`{:class="block3control"} block inside the loop.

```blocks3
when I receive [rainbow v]
repeat (15)
change [color v] effect by (pick random (20) to (30))
+wait (0.1) seconds
end
```

## Now run your code

Click on the **Rainbow**.

Check that the dumpling flashes through different colours.
