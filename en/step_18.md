## Send the clones flying

Scatter the clones across the stage.

![starfish sprite](images/star-sprite.png){:width="80px"}

You're still working on the **Starfish sprite**.

## Step 1

Add a `glide to`{:class="block3motion"} block set to 'random position'.

```blocks3
set size to (pick random (50) to (100)) %
show
+glide (0.8) secs to (random position v)
```

## Step 2

Tidy each clone away afterwards with a `delete this clone`{:class="block3control"} block.

```blocks3
show
glide (0.8) secs to (random position v)
+delete this clone
```

## Now run your code

Click on the **Starfish**.

Check that the starfish fly out across the stage and disappear.
