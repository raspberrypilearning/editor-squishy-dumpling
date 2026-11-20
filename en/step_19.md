## Delete the clones

Delete each clone so they disappear.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.

Delete each clone when it finishes gliding.

```blocks3
when I start as a clone
change [color v] effect by (pick random (0) to (255))
set size to (pick random (50) to (100)) %
go to (dumpling v)
glide (0.7) secs to (random position v)
+delete this clone
```

## Now run your code

Click on the **star**. Check that each star disappears when it stops gliding.

![Each star clone disappears when it stops gliding.](images/step-19.gif){:width="450px"}
