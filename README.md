# Shell
Recognizing shell gas stations

TODO:
- try only use the red channel since the shell logo has a lot of red (and the goal is to isolate that one), maybe filters out stuff. Do some visualization to see if the logo is clear though.
- in data exploration have to see what size the pics are, to know to what size to resize them. Right now I just do a random crop to a small image, but it's far from ideal
- Use flips or not ? THe logos are not symmetric, so maybe not.
- Only keep images with the logo ? So far I also have the ones with text too.
- If you are tuning a pretrained model, you’ll want to use Normalize to set mean and std. IN ALBUMENTATION
- Merge the cell where I create the config instance with the next one in which everything run. Or create all the things in the first cell to uniformize and not have a mixed version
- Assuming that all the images with the shell logo have pretty much the same colors, maybe we want to avoid chaning the brightness and the color intensity, etc.
- look at the list of augmentations and see which ones to choose https://albumentations.readthedocs.io/en/latest/api/augmentations.html#albumentations.augmentations.transforms.CenterCrop
- in config: add channels to the size too ?

For the interview:
Key features of this project:
- using Keras.utils.Sequence which has many advantages.
  - From the Keras documentation: Sequence are a safer way to do multiprocessing. This structure guarantees that the network will only train once on each sample per epoch which is not the case with generators.
  - Most Keras tutorials use the ImageDataGenerator class to generate batch and do image augmentation. But it doesn’t leave much room for customization and it is not fast enough. (although it would be fine for this small project...)
-
