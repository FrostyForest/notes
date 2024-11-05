# lecture5 Monte Carlo Learning
[toc]
## MC Basic
### 无模型估计
![without models](image-65.png)
![model-based methods](image-66.png)
![monte carlo](image-67.png)
![大数定律](image-68.png)
![policy iteration](image-69.png)
![action value expression](image-70.png)
![estimation of action values](image-71.png)
![mc basic algorithm](image-72.png)
![summary mc basic](image-73.png)
#### 例子
![example of mc basic](image-74.png)
![step1](image-75.png)
![step1_](image-76.png)
![step2](image-77.png)
#### episode length
![episode length](image-78.png)
![findings](image-79.png)
## MC Exploring Starts
![data efficient](image-80.png)
### when to update the policy
![when to update the policy](image-81.png)
### Generalized policy iteration
![GPI](image-82.png)
### MC Exploring Starts Algorithm
![MC Exploring Starts](image-83.png)
![problems](image-84.png)
## MC $\epsilon$-Greedy
### soft policy
![soft policy](image-85.png)
### $\epsilon$-greedy policy
![$\epsilon$-greedy policy](image-86.png)
![pseudocode](image-89.png)
### how to embed greedy into mc base
![origin](image-87.png)
![now](image-88.png)
### 探索性
![exploration](image-90.png)
![small $\epsilon$](image-91.png)

### 最优性
![optimality](image-92.png)

### 一致性
$\epsilon$太大的话策略的最优性和greedy策略的最优性不一致
![consistent](image-93.png)