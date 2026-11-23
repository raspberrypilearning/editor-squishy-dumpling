## Lift the lid

Open the basket with a click.

The starter project is open beside these instructions, with the dumpling and lid sprites ready to use.

## Step 1

Click on the **lid sprite**.

![lid sprite](images/lid-sprite.png){:width="80px"}

## Step 2

Make the lid go to the middle of the stage, in front of the dumpling, when the green flag is clicked.

![lid sprite](images/lid-sprite.png){:width="80px"}
```blocks3
+when green flag clicked
+go to x: (0) y: (0)
+go to [front v] layer
```

## Step 3

Make the lid glide up when it is clicked.

![lid sprite](images/lid-sprite.png){:width="80px"}
```blocks3
+when this sprite clicked
+glide (1) secs to x: (65) y: (120)
```

## Step 4

Let the lid wait, then glide back down.

![lid sprite](images/lid-sprite.png){:width="80px"}
```blocks3
when this sprite clicked
glide (1) secs to x: (65) y: (120)
+wait (1) seconds
+glide (1) secs to x: (0) y: (0)
```

## Step 5

Send the `lid`{:class="block3events"} message as it lifts.

![lid sprite](images/lid-sprite.png){:width="80px"}
```blocks3
when this sprite clicked
+broadcast (lid v)
glide (1) secs to x: (65) y: (120)
wait (1) seconds
glide (1) secs to x: (0) y: (0)
```

## Now run your code

Click on the **lid**. Check that it glides up, then glides back down.

![The lid glides up, then glides back down.](images/step_1.gif){:width="450px"}
