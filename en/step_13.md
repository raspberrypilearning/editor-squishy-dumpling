## Position the star

Move the star, then make it send a message when it is clicked.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.

## Step 1

On the stage, drag the star to the right.

## Step 2

Position the star using the `go to x: y:`{:class="block3motion"} block. Don't change the numbers in the block.

```blocks3
+when green flag clicked
+go to x: () y: ()
+set size to (100) %
```

## Step 3

Send a new message and name it `star`{:class="block3events"} when the star is clicked.

```blocks3
+when this sprite clicked
+broadcast (star v)
```

## Step 4

Make the star spin when it is clicked.

```blocks3
+when this sprite clicked
+repeat (24)
turn cw (15) degrees
+end
```

## Now run your code

Drag the **star** to a new place on the stage. Click the **Green Flag**. Check that the **star** goes back to where you positioned it.

Click on the **star**. Check that it spins.

![The star at the bottom right of the stage.](images/step_13.png){:width="450px"}
