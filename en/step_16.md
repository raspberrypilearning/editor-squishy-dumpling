## Make lots of stars

Make the star clones look like they are coming from the dumpling.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.

Put the `create clone of`{:class="block3control"} block in a loop so that it makes lots of clones when the star is clicked.

```blocks3
when this sprite clicked
broadcast (stars v)
+repeat (10)
create clone of (myself v)
wait (0.1) seconds
+end
```

> [!TIP]
>
> Experiment with the number in the `repeat`{:class="block3control"} block to make more stars.
>
> Try a different `wait`{:class="block3control"} time to change how quickly the stars come.

## Now run your code

Click on the **star**. Check that lots of star clones glide away from the dumpling.

![Lots of star clones glide away from the dumpling.](images/step_16.gif){:width="450px"}
