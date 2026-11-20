## Make a rainbow dumpling

Change the colours of the dumpling costume.


## Step 1

Click on the **dumpling sprite**.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 2

Check when the **rainbow** message arrives.

```blocks3
when I receive [rainbow v]
```

## Step 2

Make the colour effect change, and repeat it.

```blocks3
when I receive [rainbow v]
+repeat (15)
change [color v] effect by (25)
wait (0.1) seconds
+end
```

## Now run your code

Click on the **rainbow**. Check that the dumpling flashes through different colours.

![PLACEHOLDER: the dumpling flashes through different colours.](images/step-8.gif){:width="450px"}
