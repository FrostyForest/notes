# lecture7 Temporal-Difference Learning
[toc]

## motivating examples
![first](imgs_lesson7/image-117.png)
![second](imgs_lesson7/image-118.png)
![third](imgs_lesson7/image-119.png)
## TD learning of state values
![td-al](imgs_lesson7/image-120.png)
![td-al_2](imgs_lesson7/image-121.png)
### why $\bar{v}_t$ is called TD target
![first](imgs_lesson7/image-122.png)
### TD error
![second](imgs_lesson7/image-123.png)
### what do TD do mathmetically
It sovles the bellman equation of a given policy $\pi$
![first](imgs_lesson7/image-124.png)
![second](imgs_lesson7/image-125.png)
![rm td](imgs_lesson7/image-126.png)
![rm2](imgs_lesson7/image-127.png)
![rm3](imgs_lesson7/image-128.png)
### convergence of TD
![convergence](imgs_lesson7/image-129.png)
### TD learning and MC learning
![ad and dis](imgs_lesson7/image-130.png)
![comparison](imgs_lesson7/image-131.png)
## TD learning of action values: Sarsa
![sarsa](imgs_lesson7/image-132.png)
![explaination](imgs_lesson7/image-133.png)
![algorithm of sarsa](imgs_lesson7/image-134.png)
总而言之，就是通过某种方法能够估计此时的action value,在根据最大的action value,通过$\epsilon$-greedy方法去选择action
### examples
![task description](imgs_lesson7/image-135.png)
![results](imgs_lesson7/image-136.png)
## TD learning of action values: Expected Sarsa
![expected sarsa](imgs_lesson7/image-137.png)
![expect sarsa](imgs_lesson7/image-138.png)
## TD learning of action values: n-step Sarsa
![n-step sarsa](imgs_lesson7/image-139.png)
![dif](imgs_lesson7/image-140.png)
## TD learning of optimal action values: Q-learning
![q-learning](imgs_lesson7/image-141.png)
![mathmatically](imgs_lesson7/image-142.png)
### on-policy and off-policy
![on-off](imgs_lesson7/image-143.png)
![advantage off policy](imgs_lesson7/image-144.png)
![sarsa is on policy](imgs_lesson7/image-145.png)
![monte carlo is on policy](imgs_lesson7/image-146.png)
![q-learning is off policy](imgs_lesson7/image-147.png)

### q-learning oseudocode
![on policy](imgs_lesson7/image-148.png)
![off policy](imgs_lesson7/image-149.png)
### task description
![task](imgs_lesson7/image-150.png)
## unified view
![different TD algorithms](imgs_lesson7/image-151.png)
![equations](imgs_lesson7/image-152.png)

