## Lift the lid for the rainbow

Make the lid join in whenever the rainbow is clicked.

![lid sprite](images/lid-sprite.png){:width="80px"}

## Step 1

Click on the **lid sprite**.

## Step 2

Make the lid glide up when the message arrives.

```blocks3
+when I receive [rainbow v]
+glide (1) secs to x: (65) y: (120)
```

## Step 3

Let the lid wait, then glide back down.

```blocks3
when I receive [rainbow v]
glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

## Now run your code

Click on the **rainbow**. Check that the lid lifts while the dumpling changes colour.

![PLACEHOLDER: the lid lifts as the dumpling changes colour.](images/step-10.gif){:width="450px"}
