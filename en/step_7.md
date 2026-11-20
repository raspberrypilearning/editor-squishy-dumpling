## Make it clickable

Move the sprite and set up the click.

![rainbow sprite](images/rainbow-sprite.png){:width="80px"}

Still working in the **rainbow sprite**.

## Step 1

In the stage, position the rainbow where you want it.

> [!TIP]
>
> You can change the stage to the large view.
>
> ![The stage in the large view, with the rainbow dragged into place in front of the dumpling.](images/rainbowtip.gif){:width="450px"}

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

Send a new message called `rainbow`{:class="block3events"} when the rainbow is clicked.

```blocks3
+when this sprite clicked
+broadcast (rainbow v)
```
> [!TIP]
>
> Name the new message 'rainbow'
>
> ![The New Message window with 'rainbow' typed as the message name.](images/new-message.png){:width="450px"}

![The dumpling flashes through different colours.](images/step7.png){:width="450px"}

