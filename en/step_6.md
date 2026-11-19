## Add a rainbow button

Add a button the player can click for a rainbow effect.

![rainbow sprite](images/rainbow-sprite.png){:width="80px"}

## Step 1

Choose the **rainbow sprite** from the sprite library.

![PLACEHOLDER: choosing the rainbow sprite from the library.](images/rainbow-choose.png){:width="450px"}

## Step 2

Drag it to the bottom right of the stage.

## Step 3

Send a new message called `rainbow`{:class="block3events"} when the rainbow is clicked.

```blocks3
+when this sprite clicked
+broadcast (rainbow v)
```

The dumpling answers the message in the next step.
