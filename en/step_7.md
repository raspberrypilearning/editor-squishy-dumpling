## Make it clickable

Move the sprite and set up the click.

![rainbow sprite](images/rainbow-sprite.png){:width="80px"}

You're still working on the **rainbow sprite**.

## Step 1

On the stage, position the rainbow where you want it.

## Step 2

Click on the **Code** tab.

![The Code tab.](images/code-tab.png){:width="450px"}

## Step 3

Add the `go to x: y:`{:class="block3motion"} position in blocks, so the button starts in the same place every time.

```blocks3
+when green flag clicked
+go to x: (-153) y: (-123)
```

## Step 4

Send the message `rainbow`{:class="block3events"} when the sprite is clicked.

```blocks3
+when this sprite clicked
+broadcast (rainbow v)
```

> [!TIP]
>
> Click on the drop-down arrow and name the new message 'rainbow'.
>
> ![The New Message window with 'rainbow' typed as the message name.](images/new-message-rainbow.png){:width="450px"}

## Now run your code

Click the **Green Flag**. Check that the **rainbow** goes to the bottom left of the stage.

![The rainbow at the bottom left of the stage.](images/step_7.png){:width="450px"}

