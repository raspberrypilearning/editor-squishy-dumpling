## Lift the lid for the starfish

Make the lid join in for the starfish shower as well.

![lid sprite](images/lid-sprite.png){:width="80px"}

## Step 1

Click on the **Lid sprite**.

Add a `when I receive`{:class="block3events"} block set to `stars`{:class="block3events"}, and a `glide`{:class="block3motion"} block.

```blocks3
+when I receive [stars v]
+glide (1) secs to x: (65) y: (120)
```

## Step 2

Bring the lid back down with a `wait`{:class="block3control"} block and a second `glide`{:class="block3motion"} block.

```blocks3
when I receive [stars v]
glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

## Now run your code

Click on the **Starfish**.

Check that the lid lifts while the dumpling spins and the starfish fly.
