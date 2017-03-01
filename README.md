# P3 - Behavioural-Cloning

## README

---

Refer to P3_Behavioural-Cloning.ipynb for detailed writeup of steps taken to complete the project.

Things to note when forking the repository and participating in the learning of how to train a self driving car.

1. The Udacity Self Driving Car Simulator can be found [here](https://github.com/udacity/self-driving-car-sim). A few pointers to note during collection of driving data include:

  * the car should stay in the center of the road as much as possible
  * if the car veers off to the side, it should recover back to center
  * driving counter-clockwise can help the model generalize

2. When running through Step 1 of data exploration in P3_Behavioural-Cloning.ipynb, be sure to modify codes to read from the correct folder as it is stored in your computer. Also note the possible change in file path in driving_log.csv. The current folder structure adopted is as follows:

	```
	P3_Behavioural-Cloning.ipynb
	drive.py
	├── data/
	│   ├── IMG/
	│   ├── driving_log.csv
	├── nvidia_model/
	│   ├── Example (nvidia1.json and nvidia1.h5)
	├── vgg16_model/
	│   ├── Example (vgg161.json and vgg161.h5)
	├── vivek_model/
	│   ├── Example (vivek1.json and vivek1.h5)
	``` 

3. To run Udacity simulator in autonomous mode, type `python drive.py filepath.json`

