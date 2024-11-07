# lecture5 Monte Carlo Learning
[toc]
## MC Basic
### 无模型估计
![without models](imgs_lesson5/image-65.png)
![model-based methods](imgs_lesson5/image-66.png)
![monte carlo](imgs_lesson5/image-67.png)
![大数定律](imgs_lesson5/image-68.png)
![policy iteration](imgs_lesson5/image-69.png)
![action value expression](imgs_lesson5/image-70.png)
![estimation of action values](imgs_lesson5/image-71.png)
![mc basic algorithm](imgs_lesson5/image-72.png)
![summary mc basic](imgs_lesson5/image-73.png)
#### 例子
![example of mc basic](imgs_lesson5/image-74.png)
![step1](imgs_lesson5/image-75.png)
![step1_](imgs_lesson5/image-76.png)
![step2](imgs_lesson5/image-77.png)
#### episode length
![episode length](imgs_lesson5/image-78.png)
![findings](imgs_lesson5/image-79.png)
## MC Exploring Starts
![data efficient](imgs_lesson5/image-80.png)
### when to update the policy
![when to update the policy](imgs_lesson5/image-81.png)
### Generalized policy iteration
![GPI](imgs_lesson5/image-82.png)
### MC Exploring Starts Algorithm
![MC Exploring Starts](imgs_lesson5/image-83.png)
![problems](imgs_lesson5/image-84.png)
## MC $\epsilon$-Greedy
### soft policy
![soft policy](imgs_lesson5/image-85.png)
### $\epsilon$-greedy policy
![$\epsilon$-greedy policy](imgs_lesson5/image-86.png)
![pseudocode](imgs_lesson5/image-89.png)
### how to embed greedy into mc base
![origin](imgs_lesson5/image-87.png)
![now](imgs_lesson5/image-88.png)
### 探索性
![exploration](imgs_lesson5/image-90.png)
![small $\epsilon$](imgs_lesson5/image-91.png)

### 最优性
![optimality](imgs_lesson5/image-92.png)

### 一致性
$\epsilon$太大的话策略的最优性和greedy策略的最优性不一致
![consistent](imgs_lesson5/image-93.png)