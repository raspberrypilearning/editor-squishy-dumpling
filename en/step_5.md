## Add a squishy sound

Play a sound while the dumpling is squashed.

![dumpling sprite](images/dumpling-sprite.png){:width="80px"}

## Step 1

Open the **Sounds** tab.

![The Sounds tab.](images/sounds-tab.png){:width="450px"}

## Step 2

Click **Choose a Sound**.

![Choosing a sound.](images/sounds-choose.png){:width="250px"}

## Step 3

Pick a squishy sound from the library.

![The Choose a Sound library.](images/sounds-list.png){:width="450px"}

## Step 4

Back in the **Code** tab, play your sound as the squash starts.

```blocks3
when I receive [dumpling clicked v]
+start sound (squishy v)
repeat (15)
next costume
wait (0.1) seconds
end
switch costume to (costume 1 v)
```

## Now run your code

Click on the **lid**. Check that your sound plays while the dumpling squashes.

![PLACEHOLDER: the dumpling squashes with a sound.](images/step-5.gif){:width="450px"}
