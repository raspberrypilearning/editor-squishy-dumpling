## Set up each clone

Hide each clone behind the dumpling until it is ready to appear.

![starfish sprite](images/star-sprite.png){:width="80px"}

You're still working on the **Starfish sprite**.

## Step 1

Add a `when I start as a clone`{:class="block3control"} block and a `hide`{:class="block3looks"} block.

```blocks3
+when I start as a clone
+hide
```

## Step 2

Move each clone behind the dumpling with a `go to layer`{:class="block3looks"} block and a `go to`{:class="block3motion"} block set to **Dumpling**.

```blocks3
when I start as a clone
hide
+go to [back v] layer
+go to (Dumpling v)
```

The clones are hidden for now, and appear in the next step.
