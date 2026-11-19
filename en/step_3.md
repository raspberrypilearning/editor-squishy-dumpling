## Squash the dumpling

Squash the dumpling by swapping between its costumes.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 1

Click on the **dumpling sprite**.

## Step 2

Swap the dumpling's costumes 15 times when the message arrives.

```blocks3
+when I receive [dumpling clicked v]
+repeat (15)
+next costume
+end
```

## Step 3

Slow the swap down.

```blocks3
when I receive [dumpling clicked v]
repeat (15)
next costume
+wait (0.1) seconds
end
```

## Now run your code

Click on the **lid**. Check that the dumpling squashes and stretches.

![PLACEHOLDER: the dumpling squashes and stretches when the lid is clicked.](images/step-3.gif){:width="450px"}
