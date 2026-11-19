## Change colour

Flash the dumpling through lots of colours.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 1

Click on the **dumpling sprite**.

## Step 2

Change the dumpling's colour 15 times when the message arrives.

```blocks3
+when I receive [rainbow v]
+repeat (15)
+change [color v] effect by (pick random (20) to (30))
+end
```

## Step 3

Slow the colour change down.

```blocks3
when I receive [rainbow v]
repeat (15)
change [color v] effect by (pick random (20) to (30))
+wait (0.1) seconds
end
```

## Now run your code

Click on the **rainbow**. Check that the dumpling flashes through different colours.

![PLACEHOLDER: the dumpling flashes through different colours.](images/step-7.gif){:width="450px"}
