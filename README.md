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

### How to train the agent

Also in the Navigation repository, just run the cells except the ```!pip -q install ./python``` (If you have runned it before). All the imports will be made and the training will start.
