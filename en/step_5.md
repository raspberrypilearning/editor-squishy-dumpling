## Play your sound

Make your recording play while the dumpling is squashed.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **dumpling sprite**.

Back in the **Code** tab, play your sound as the squash starts.

```blocks3
when I receive [lid clicked v]
+start sound (squishy v)
repeat (15)
next costume
wait (0.1) seconds
end
switch costume to (costume 1 v)
```

## Now run your code

Click on the **lid**. Check that your sound plays while the dumpling squashes.

![PLACEHOLDER: the dumpling squashes with a sound.](images/step-5.gif){:width="450px"}
