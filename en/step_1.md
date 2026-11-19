## Lift the lid

Open the basket with a click.

![lid sprite](images/lid-sprite.png){:width="80px"}

The starter project is open beside these instructions, with all the sprites you need.

## Step 1

Click on the **Lid sprite**, it has some blocks to get you started.

Add a `when this sprite clicked`{:class="block3events"} block and a `glide`{:class="block3motion"} block.

```blocks3
+when this sprite clicked
+glide (1) secs to x: (65) y: (120)
```

## Step 2

Make the lid settle back down with a `wait`{:class="block3control"} block and a second `glide`{:class="block3motion"} block.

```blocks3
when this sprite clicked
glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

## Now run your code

Click on the **Lid**.

Check that it lifts up and settles back down.
