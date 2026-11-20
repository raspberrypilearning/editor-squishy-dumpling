## Make a star clone

Make a clone of the star above the dumpling.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.

## Step 1

Make a clone of the star when it is clicked.

```blocks3
when this sprite clicked
broadcast (stars v)
+create clone of (myself v)
```

## Step 2

When the clone starts, move it to the dumpling, then glide.

```blocks3
+when I start as a clone
+go to (dumpling v)
+glide (0.7) secs to (random position v)
```

## Now run your code

Click on the **star**. Check that a star clone glides away from the dumpling.

![A star clone glides away from the dumpling.](images/step-15.gif){:width="450px"}
