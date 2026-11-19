## Squash the dumpling

Squash the dumpling by swapping between its costumes.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 1

Click on the **Dumpling sprite**.

Add a `when I receive`{:class="block3events"} block set to `dumpling clicked`{:class="block3events"}, and a `repeat`{:class="block3control"} loop with a `next costume`{:class="block3looks"} block inside.

```blocks3
+when I receive [dumpling clicked v]
+repeat (15)
+next costume
+end
```

## Step 2

Slow the squash down with a `wait`{:class="block3control"} block inside the loop.

```blocks3
when I receive [dumpling clicked v]
repeat (15)
next costume
+wait (0.1) seconds
end
```

## Now run your code

Click on the **Lid**.

Check that the dumpling squashes and stretches.
