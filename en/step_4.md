## Back to a smile

Finish on the same costume every time, so the dumpling always ends up smiling.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **Dumpling sprite**.

Add a `switch costume to`{:class="block3looks"} block under the loop.

```blocks3
when I receive [dumpling clicked v]
repeat (15)
next costume
wait (0.1) seconds
end
+switch costume to (7 v)
```

## Now run your code

Click on the **Lid**.

Check that the dumpling goes back to its smiling costume at the end.
