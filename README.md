# Shell
Recognizing shell gas stations

TODO:
- compare a model trained by me with a pretrained model in which I just fine-tune the classifier. If you are tuning a pretrained model, you’ll want to use Normalize to set mean and std. IN ALBUMENTATION
- add dropout ? MOre generally play with other models
- Enlarge the data set! --> add more categories
- hyperparam tuning : batch_size, factorreduceLR, LR, architecture, 
- save tensorboard somehow (it resets after each fold) - can ask if I want to continue

For the interview:
Key features of this project:
- using Keras.utils.Sequence which has many advantages.
  - From the Keras documentation: Sequence are a safer way to do multiprocessing. This structure guarantees that the network will only train once on each sample per epoch which is not the case with generators.
  - Most Keras tutorials use the ImageDataGenerator class to generate batch and do image augmentation. But it doesn’t leave much room for customization and it is not fast enough. (although it would be fine for this small project...)
-

Ways to improve:
- data augmentation: 
  - less aug on val set ?
  - more aug on train set for more reg ?
- enlarge the dataset
- remove some low res photos, which would increase the min res and thus have the photos less blurry (because resized to bigger)
- during predictions : take mode of prediction instead of geometric mean of probabilities

For pres:
- say about when I freaked out because all was pred chevron on test. It was because the image was loading weird.
