# Shell
Recognizing shell gas stations

TODO:
- try only use the red channel since the shell logo has a lot of red (and the goal is to isolate that one), maybe filters out stuff. Do some visualization to see if the logo is clear though.
- Only keep images with the logo ? So far I also have the ones with text too.
- If you are tuning a pretrained model, you’ll want to use Normalize to set mean and std. IN ALBUMENTATION
- Assuming that all the images with the shell logo have pretty much the same colors, maybe we want to avoid chaning the brightness and the color intensity, etc.
- change color labels for figures as they're black and we can't see them well
- show missclassified pictures
- show pictures in visualization to see some samples
- compare a model trained by me with a pretrained model in which I just fine-tune the classifier
- also data visualize some cropped images to see what he sees (this cropping adds a lot of reg ?)
- add dropout ? MOre generally play with other models
- during predictions, do 5 of them or so and then take geom mean of predicition scores (to eliminate some variance due to the cropping). And then do another geom mean (or do only a big geom mean) with all the folds
- Enlarge the data set!

For the interview:
Key features of this project:
- using Keras.utils.Sequence which has many advantages.
  - From the Keras documentation: Sequence are a safer way to do multiprocessing. This structure guarantees that the network will only train once on each sample per epoch which is not the case with generators.
  - Most Keras tutorials use the ImageDataGenerator class to generate batch and do image augmentation. But it doesn’t leave much room for customization and it is not fast enough. (although it would be fine for this small project...)
-
