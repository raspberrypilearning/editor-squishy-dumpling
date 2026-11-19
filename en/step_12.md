## Spin the dumpling

Send the dumpling spinning round and round.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

Click on the **Dumpling sprite**.

Add a `when I receive`{:class="block3events"} block set to `stars`{:class="block3events"}, and a `repeat`{:class="block3control"} loop with a `turn`{:class="block3motion"} block inside.

```blocks3
+when I receive [stars v]
+repeat (85)
+turn cw (15) degrees
+end
```

## Now run your code

Click on the **Starfish**.

Check that the dumpling spins round.
