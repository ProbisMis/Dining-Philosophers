# Dining-Philosophers

Dining Philosophers problem is an example problem for  synchronization issues and techniques for resolving them in Operating Systems.
We implemented this in Operating Systems but all GUI such as forks, plates etc.  were given by course instructor as well as their placement in GUI. What we have done is resolving the synchronization issues by using semaphores and mutual exclusion.  


Idea is,  no consecutive philosopher can eat at the same time. If one philosopher is eating and if that philosopher is consecutive to you. You have to wait him to finish, after a fork is available. You may eat. In other words, a philosopher needs TWO forks to EAT.  Lets visiualise and it will be more clear ; 


![diningphilosophers](https://github.com/ProbisMis/Dining-Philosophers/blob/master/ice_screenshot_20190124-120539.png)

* Yellow - State of Hungry
* Red    - State of Eating
* Black  - State of Thinking

