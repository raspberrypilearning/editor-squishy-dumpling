## Lift the lid for the star

Make the lid move when the star is clicked.

## Step 1

Click on the **lid sprite**.

![lid sprite](images/lid-sprite.png){:width="80px"}

## Step 2

Make the lid glide up when it receives the `star`{:class="block3events"} message. It waits, then glides back down.

```blocks3
+when I receive [star v]
+glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

> [!TIP]
>
> Right-click to duplicate the `when I receive rainbow`{:class="block3events"} script, then choose 'star' from the drop-down menu.
>
> ![The when I receive rainbow script is duplicated, and the message is changed to star.](images/star-lid.gif){:width="450px"}

## Now run your code

Click on the **star**. Check that the lid glides up, then glides back down.

![The lid glides up, then glides back down, when the star is clicked.](images/step_14.gif){:width="450px"}
