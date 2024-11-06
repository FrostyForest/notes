# lecture7 Temporal-Difference Learning
[toc]

## motivating examples
![first](image-117.png)
![second](image-118.png)
![third](image-119.png)
## TD learning of state values
![td-al](image-120.png)
![td-al_2](image-121.png)
### why $\bar{v}_t$ is called TD target
![first](image-122.png)
### TD error
![second](image-123.png)
### what do TD do mathmetically
It sovles the bellman equation of a given policy $\pi$
![first](image-124.png)
![second](image-125.png)
![rm td](image-126.png)
![rm2](image-127.png)
![rm3](image-128.png)
### convergence of TD
![convergence](image-129.png)
### TD learning and MC learning
![ad and dis](image-130.png)
![comparison](image-131.png)
## TD learning of action values: Sarsa
![sarsa](image-132.png)
![explaination](image-133.png)
![algorithm of sarsa](image-134.png)
总而言之，就是通过某种方法能够估计此时的action value,在根据最大的action value,通过$\epsilon$-greedy方法去选择action
### examples
![task description](image-135.png)
![results](image-136.png)
## TD learning of action values: Expected Sarsa
![expected sarsa](image-137.png)
![expect sarsa](image-138.png)
## TD learning of action values: n-step Sarsa
![n-step sarsa](image-139.png)
![dif](image-140.png)
## TD learning of optimal action values: Q-learning
![q-learning](image-141.png)
![mathmatically](image-142.png)
### on-policy and off-policy
![on-off](image-143.png)
![advantage off policy](image-144.png)
![sarsa is on policy](image-145.png)
![monte carlo is on policy](image-146.png)
![q-learning is off policy](image-147.png)

### q-learning oseudocode
![on policy](image-148.png)
![off policy](image-149.png)
### task description
![task](image-150.png)
## unified view
![different TD algorithms](image-151.png)
![equations](image-152.png)