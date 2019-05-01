# Shell
Recognizing shell gas stations


For the interview:
Key features of this project:
- using Keras.utils.Sequence which has many advantages.
  - From the Keras documentation: Sequence are a safer way to do multiprocessing. This structure guarantees that the network will only train once on each sample per epoch which is not the case with generators.
  - Most Keras tutorials use the ImageDataGenerator class to generate batch and do image augmentation. But it doesn’t leave much room for customization and it is not fast enough. (although it would be fine for this small project...)
-
