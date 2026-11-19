## Lift the lid for the rainbow

Make the lid join in whenever the rainbow is clicked.

![lid sprite](images/lid-sprite.png){:width="80px"}

## Step 1

Click on the **Lid sprite**.

Add a `when I receive`{:class="block3events"} block set to `rainbow`{:class="block3events"}, and a `glide`{:class="block3motion"} block.

```blocks3
+when I receive [rainbow v]
+glide (1) secs to x: (65) y: (120)
```

## Step 2

Bring the lid back down with a `wait`{:class="block3control"} block and a second `glide`{:class="block3motion"} block.

```blocks3
when I receive [rainbow v]
glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

## Now run your code

Click on the **Rainbow**.

Check that the lid lifts while the dumpling changes colour.
