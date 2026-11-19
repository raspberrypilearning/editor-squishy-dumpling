## Back to yellow

Set the colour back to normal at the end, so the dumpling starts yellow every time.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **Dumpling sprite**.

Add a `set effect to`{:class="block3looks"} block under the loop.

```blocks3
when I receive [rainbow v]
repeat (15)
change [color v] effect by (pick random (20) to (30))
wait (0.1) seconds
end
+set [color v] effect to (0)
```

## Now run your code

Click on the **Rainbow**.

Check that the dumpling is yellow again at the end.
