## Make every clone different

Give each copy its own colour and size, so no two are the same.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.

## Step 1

Pick a random colour and size for each copy.

```blocks3
when I start as a clone
hide
go to [back v] layer
go to (dumpling v)
+change [color v] effect by (pick random (0) to (255))
+set size to (pick random (50) to (100)) %
```

## Step 2

Bring the copy into view.

```blocks3
change [color v] effect by (pick random (0) to (255))
set size to (pick random (50) to (100)) %
+show
```

## Now run your code

Click on the **star**. Check that a pile of different stars appears behind the dumpling.

![PLACEHOLDER: a pile of different stars appears behind the dumpling.](images/step-17.gif){:width="450px"}
