## Add a rainbow sound

Play a sound while the colours change.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **dumpling sprite**.

Play a sound as the colours start to change.

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

Click on the **rainbow**. Check that your sound plays while the colours change.

![The dumpling changes colour with a sound.](images/step-11.gif){:width="450px"}
