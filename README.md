# Shell
Recognizing shell gas stations

TODO:
- If you are tuning a pretrained model, you’ll want to use Normalize to set mean and std. IN ALBUMENTATION
- compare a model trained by me with a pretrained model in which I just fine-tune the classifier
- add dropout ? MOre generally play with other models
- during predictions, maybe take the largest prediction ?
- Enlarge the data set!
- for less blury : try to remove the photos with low res
- hyperparam tuning : batch_size, factorreduceLR, LR, architecture, 
- save tensorboard somehow (it resets after each fold) - can ask if I want to continue
- data aug for val-set ?

For the interview:
Key features of this project:
- using Keras.utils.Sequence which has many advantages.
  - From the Keras documentation: Sequence are a safer way to do multiprocessing. This structure guarantees that the network will only train once on each sample per epoch which is not the case with generators.
  - Most Keras tutorials use the ImageDataGenerator class to generate batch and do image augmentation. But it doesn’t leave much room for customization and it is not fast enough. (although it would be fine for this small project...)
-
