## Play your sound

Make your recording play when clicking the dumpling.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **dumpling sprite**.

## Step 1

Clcik back in the **Code** tab, 


## Step 2

Play your sound before the animation starts.

```blocks3
when I receive [lid v]
+start sound (squishy v)
repeat (15)
next costume
wait (0.1) seconds
end
switch costume to (costume 1 v)
```

## Now run your code

Click on the **lid**. Check that your sound plays while the dumpling animates.

![The dumpling animates with a sound.](images/step-5.gif){:width="450px"}
