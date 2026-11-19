## Add a starfish button

Add a second button for a shower of starfish.

![starfish sprite](images/star-sprite.png){:width="80px"}

## Step 1

Choose the **Starfish sprite** from the sprite library.

Drag it to the bottom left of the stage.

## Step 2

Add a `when this sprite clicked`{:class="block3events"} block and a `broadcast`{:class="block3events"} block set to a new message called `stars`{:class="block3events"}.

```blocks3
+when this sprite clicked
+broadcast (stars v)
```

The dumpling answers the message in the next step.
