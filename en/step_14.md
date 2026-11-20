## Lift the lid for the star

Make the lid move when the star is clicked.

![lid sprite](images/lid-sprite.png){:width="80px"}

## Step 1

Click on the **lid sprite**.

## Step 2

Make the lid glide up when it receives the `stars`{:class="block3events"} message.

```blocks3
+when I receive [stars v]
+glide (1) secs to x: (65) y: (120)
```

![The when I receive rainbow script is duplicated, and the message is changed to stars.](images/star-lid.gif){:width="450px"}

## Step 3

Make the lid wait, then glide back down.

```blocks3
when I receive [stars v]
glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

## Now run your code

Click on the **star**. Check that the lid glides up, then glides back down.

![The lid glides up, then glides back down, when the star is clicked.](images/step-14.gif){:width="450px"}
