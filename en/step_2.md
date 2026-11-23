## Animate the dumpling

Animate the dumpling by swapping between its costumes.

## Step 1

Click on the **dumpling sprite**.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 2

Make the dumpling swap costumes when it gets the `lid`{:class="block3events"} message.

```blocks3
+when I receive [lid v]
+repeat (15)
next costume
wait (0.1) seconds
+end
```

> [!TIP]
>
> Experiment with the number in the `repeat`{:class="block3control"} block to make the animation longer or shorter.

## Step 3

Go back to the first costume at the end.

```blocks3
when I receive [lid v]
repeat (15)
next costume
wait (0.1) seconds
end
+switch costume to (costume 1 v)
```

## Now run your code

Click on the **lid**. Check that the dumpling animates.

![The dumpling animates when the lid is clicked.](images/step_2.gif){:width="450px"}
