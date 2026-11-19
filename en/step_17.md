## Make every clone different

Give each clone its own colour and size, so no two are the same.

![starfish sprite](images/star-sprite.png){:width="80px"}

You're still working on the **Starfish sprite**.

## Step 1

Add a `change effect by`{:class="block3looks"} block and a `set size to`{:class="block3looks"} block, both with a `pick random`{:class="block3operators"} block inside.

```blocks3
when I start as a clone
hide
go to [back v] layer
go to (Dumpling v)
+change [color v] effect by (pick random (0) to (255))
+set size to (pick random (50) to (100)) %
```

## Step 2

Bring the clone into view with a `show`{:class="block3looks"} block.

```blocks3
change [color v] effect by (pick random (0) to (255))
set size to (pick random (50) to (100)) %
+show
```

## Now run your code

Click on the **Starfish**.

Check that a pile of different starfish appears behind the dumpling.
