## Add a rainbow sound

Play a sound while the colours change.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **Dumpling sprite**.

Add a `start sound`{:class="block3sound"} block to the top of the rainbow script and choose a sound.

```blocks3
when I receive [rainbow v]
+start sound (oh a rainbow v)
repeat (15)
change [color v] effect by (pick random (20) to (30))
wait (0.1) seconds
end
set [color v] effect to (0)
```

> [!TIP]
>
> Open the **Sounds** tab to add another sound from the library.

## Now run your code

Click on the **Rainbow**.

Check that your sound plays while the colours change.
