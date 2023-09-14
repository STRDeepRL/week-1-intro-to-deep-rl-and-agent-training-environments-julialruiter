____________________________
Task 1:

The original value of 0.2 for "invalid_pickup_dense_penalty" was noted as being too high, though I had a difficult time figuring out how to appropriately scale it down while playing around with manual control.   Via manual control, a perfect game netted me 1.49 points. 

The accessible part of the playing grid is 36 squares, so allowing a false pickup on every non-key square (35), could imply that the penalty should be 1.49/35...but that does not consider the actor backtracking.  Regardless, I used an approximation of this value (0.05) as the new penalty.

One thing worth noting, though, is that this value only allows for penalties coming from false pick ups--if more false actions are to be penalized (bumping into a wall, etc), then this penalty should scale down.
____________________________
Task 2:

I am having difficulties running the training script on my host machine, BUT! it runs in Google Colab.  However, Google Colab has been showing "403 error" for the tensorboard for 2 days now, and I haven't (yet) figured out how to debug it.

____________________________
Task 3:

Tensorboard is not accesible (still) :/

