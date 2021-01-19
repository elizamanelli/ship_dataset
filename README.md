# ship_dataset
The code provided here serves as an example of how to download satellite imagery from planet.com to form a dataset. The dataset created here is of images either including ships or not and can be used to train a ship recognition model.

The notebooks contains detailed steps and instructions. Even though it's not always perfectly clean - sorry for that!

The full story of this code and it's application purpose can be found in my blogpost: 
Please read it to understand the thought process behind the code :)

Here are also some known issues found from visual dataset inspection.

## Known issues:
- Some wrong labeled non-ships are downloaded and created. Those were found using visual inspection. It was pretty obvious.
- We do have some cloud covered datapoints.
- In some ship samples we cannot see the ship - This can be due to ship size, wrong AIS data or the ship moved to far in the past minute.
