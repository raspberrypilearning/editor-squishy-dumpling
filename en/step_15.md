## Make starfish clones

Make copies of the starfish to shower over the dumpling.

![starfish sprite](images/star-sprite.png){:width="80px"}

Click on the **Starfish sprite**.

Add a `repeat`{:class="block3control"} loop with a `create clone of`{:class="block3control"} block and a `wait`{:class="block3control"} block inside.

```blocks3
when this sprite clicked
broadcast (stars v)
+repeat (15)
+create clone of (myself v)
+wait (0.1) seconds
+end
```

The clones all sit on top of each other until you move them in the next steps.
