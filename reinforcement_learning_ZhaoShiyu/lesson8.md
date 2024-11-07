# lecture8 Value Function Approximation
[toc]
## motivating example
### tables
![tables](imgs_lesson8/image-153.png)
### functions
![example](imgs_lesson8/image-154.png)
![straight_line](imgs_lesson8/image-155.png)
![second order curve](imgs_lesson8/image-156.png)
![advantages](imgs_lesson8/image-157.png)
## Algorithm for state value estimation
### objective function
![objective function](imgs_lesson8/image-158.png)
#### uniform distribution
![uniform distribution](imgs_lesson8/image-159.png)
#### stationary distribution
![stationary distribution](imgs_lesson8/image-160.png)
![d_s](imgs_lesson8/image-161.png)
### 优化算法
![optimization algorithm](imgs_lesson8/image-162.png)
![al2](imgs_lesson8/image-163.png)
![al3](imgs_lesson8/image-164.png)
### 近似函数的选择
![function selection](imgs_lesson8/image-165.png)
![linear](imgs_lesson8/image-166.png)
![tabular is linear](imgs_lesson8/image-167.png)
### examples
![example](imgs_lesson8/image-168.png)
![ground truth](imgs_lesson8/image-169.png)
![td-linear](imgs_lesson8/image-170.png)
![high order](imgs_lesson8/image-171.png)
![results](imgs_lesson8/image-172.png)
### summary of the story
![summary](imgs_lesson8/image-173.png)
## Sarsa with function approximation
![al](imgs_lesson8/image-174.png)
## Q-learning with fucntion approximation
![pseudocode](imgs_lesson8/image-175.png)
## Deep Q-learning
![dqn](imgs_lesson8/image-176.png)
### objective function
![bellman optimality error](imgs_lesson8/image-177.png)
### minimize objective function
![gd](imgs_lesson8/image-178.png)
#### two networks
![trick](imgs_lesson8/image-179.png)
![first  technique](imgs_lesson8/image-180.png)
#### experience replay
![second technique](imgs_lesson8/image-181.png)
![reason](imgs_lesson8/image-182.png)
![reason2](imgs_lesson8/image-183.png)
![explain](imgs_lesson8/image-184.png)

### off policy dqn
![off policy](imgs_lesson8/image-185.png)
![results](imgs_lesson8/image-186.png)