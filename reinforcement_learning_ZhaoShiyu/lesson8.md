# lecture8 Value Function Approximation
[toc]
## motivating example
### tables
![tables](image-153.png)
### functions
![example](image-154.png)
![straight_line](image-155.png)
![second order curve](image-156.png)
![advantages](image-157.png)
## Algorithm for state value estimation
### objective function
![objective function](image-158.png)
#### uniform distribution
![uniform distribution](image-159.png)
#### stationary distribution
![stationary distribution](image-160.png)
![d_s](image-161.png)
### 优化算法
![optimization algorithm](image-162.png)
![al2](image-163.png)
![al3](image-164.png)
### 近似函数的选择
![function selection](image-165.png)
![linear](image-166.png)
![tabular is linear](image-167.png)
### examples
![example](image-168.png)
![ground truth](image-169.png)
![td-linear](image-170.png)
![high order](image-171.png)
![results](image-172.png)
### summary of the story
![summary](image-173.png)
## Sarsa with function approximation
![al](image-174.png)
## Q-learning with fucntion approximation
![pseudocode](image-175.png)
## Deep Q-learning
![dqn](image-176.png)
### objective function
![bellman optimality error](image-177.png)
### minimize objective function
![gd](image-178.png)
#### two networks
![trick](image-179.png)
![first  technique](image-180.png)
#### experience replay
![second technique](image-181.png)
![reason](image-182.png)
![reason2](image-183.png)
![explain](image-184.png)

### off policy dqn
![off policy](image-185.png)
![results](image-186.png)