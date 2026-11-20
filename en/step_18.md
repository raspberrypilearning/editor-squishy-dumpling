## Random styles

Randomise the colour effect and size.

![star sprite](images/star-sprite.png){:width="80px"}

You're still working on the **star sprite**.


Make the colour and size random with `pick random`{:class="block3operators"} blocks.

```blocks3
when I start as a clone
+change [color v] effect by (pick random (0) to (255))
+set size to (pick random (50) to (100)) %
go to (dumpling v)
glide (0.7) secs to (random position v)
```
>
> You can try other effects by clicking the 'color' drop-down menu.


## Now run your code

Click on the **star**. Check that each star clone is a rand colour and size.

![Star clones of different colours and sizes glide away from the dumpling.](images/step-18.gif){:width="450px"}
