# lecture10 Actor-Critic Methods
[toc]
## the simplest Actor-Critic(QAC)
![revisit](imgs_lesson10/image.png)
### how to get $q_t(s_t,a_t)$
![q_t](imgs_lesson10/image-1.png)
### QAC
![qac](imgs_lesson10/image-2.png)
## Advantage Actor-Critic(A2C)
![A2C](imgs_lesson10/image-3.png)
### why baseline
![first_reason](imgs_lesson10/image-4.png)
![second_reason](imgs_lesson10/image-5.png)
![goal](imgs_lesson10/image-6.png)
### baseline
![baseline](imgs_lesson10/image-7.png)
### advantage function
![advantage_function](imgs_lesson10/image-8.png)
![step](imgs_lesson10/image-9.png)
### one value network is enough
![one network](imgs_lesson10/image-10.png)
### A2C or TD actor-critic
![A2C](imgs_lesson10/image-11.png)
## Importance sampling and off-policy Actor-Critic
### how to estimate $E(x)$ by using samples $\{x_i\}$
![how estimate](imgs_lesson10/image-12.png)
#### case1
![ase1](imgs_lesson10/image-13.png)
#### case2
![case2](imgs_lesson10/image-14.png)
#### how
![how](imgs_lesson10/image-15.png)
### Importance Sampling
![importance sampling](imgs_lesson10/image-16.png)
![importance sampling2](imgs_lesson10/image-17.png)
![summary](imgs_lesson10/image-18.png)
#### off policy gradient
![off policy](imgs_lesson10/image-19.png)

#### off policy actor-critic
![al](imgs_lesson10/image-21.png)
![code](imgs_lesson10/image-20.png)
## Deterministic Actor-Critic(DPG)
![introduction](imgs_lesson10/image-22.png)
![al](imgs_lesson10/image-23.png)
![al2](imgs_lesson10/image-24.png)
![remarks](imgs_lesson10/image-25.png)