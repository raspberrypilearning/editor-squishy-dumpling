## Send the clones flying

Scatter the copies across the stage.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.

## Step 1

Send each copy gliding to a random spot.

```blocks3
set size to (pick random (50) to (100)) %
show
+glide (0.8) secs to (random position v)
```

## Step 2

Tidy each copy away when it gets there.

```blocks3
show
glide (0.8) secs to (random position v)
+delete this clone
```

## Now run your code

Click on the **star**. Check that the stars fly out across the stage and disappear.

![PLACEHOLDER: stars fly out across the stage and disappear.](images/step-19.gif){:width="450px"}
