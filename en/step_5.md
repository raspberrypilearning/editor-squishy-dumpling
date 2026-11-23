## Play your sound

Make your recording play when the lid is clicked.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

You're still working on the **dumpling sprite**.

## Step 1

Click on the **Code** tab.

![The Code tab.](images/code-tab.png){:width="450px"}

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
