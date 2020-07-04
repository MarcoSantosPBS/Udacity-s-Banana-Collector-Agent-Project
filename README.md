# Udacity's Banana Collector Agent Project

### Environment

This Agent was created to solve the problem of unity's ML Banana environment where the goal of the agent is to collect the max amount of yellow bananas while avoiding the blue ones

The state is composed by 37 informations 

***States look like***: [ 1.,  0.,  0., 0.,  0.84408134,  0.,  0.,
1.,  0.,  0.0748472,  0.,  1.,  0.,  0.
0.25755,  1.,  0.,  0.,  0., .74177343
0.,  1.,  0.,  0.,  0.25854847,  0.,  0.
1.,  0.,  0.09355672,  0.,  1.,  0.,  0.
0.31969345,  0.,  0.]

***States have length***: 37

And there are four possible actions the agent can make. 
The environment is considered solved when the agent achives a average reward of 13+ after 100 episodes


### Instaling the environment 

In the cmd access the python folder, an easy way to do this is access the folder throught the explorer and in the bar address bar, the one showing the path to the folder type ```cmd --admin```. In the cmd type ```pip install -r requirements.txt``` and the dependencies will be installed

Then, you have to download the environment from one of the links below. You need only select the environment that matches your operating system:

- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

### How to train the agent

Also in the Navigation repository, just run the cells except the ```!pip -q install ./python``` (If you have runned it before). All the imports will be made and the training will start.
