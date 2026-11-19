## Add a star button

Add a second button for a shower of stars.

![star sprite](images/star-sprite.png){:width="80px"}

## Step 1

Choose the **star sprite** from the sprite library.

![PLACEHOLDER: choosing the star sprite from the library.](images/star-choose.png){:width="450px"}

## Step 2

Drag it to the bottom left of the stage.

## Step 3

Send a new message called `stars`{:class="block3events"} when the star is clicked.

```blocks3
+when this sprite clicked
+broadcast (stars v)
```

The dumpling answers the message in the next step.
