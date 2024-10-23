# Lecture2 Bellmen Equation
[toc]
![Outline1](image.png)

![outline2](image-1.png)

![return calculate](image-2.png)
![return calculate method 1](image-3.png)
![return calculate method 2](image-4.png)
![Bellman equation](image-5.png)

## state value
### discounted return $G_t$
![discounted return](image-6.png)
### state value
某策略$\pi$在某状况$s$的state value为$G_t$的期望
$$
v_{\pi}(s)=E[G_t|S_t=s]
$$
## Bellman equation
### 公式推导
![deriving the bellman](image-7.png)
![first term](image-8.png)
![second term](image-9.png)
![bellman equation](image-10.png)
![highlight](image-11.png)
### Bellman equation的矩阵和向量形式
![matrix form](image-12.png)
![matrix form](image-13.png)
![matrix example](image-14.png)
### 求解 state value
为什么要求解state value,因为要做policy evaluation
* policy evaluation：给定一个策略，求出其对应的state value
![solve state values](image-15.png)
## action value
### action value and state value
![state value and action value](image-16.png)
### definition
![action value definition1](image-17.png)
![action value definition2](image-18.png)
![action value highlight](image-19.png)
## 总结
![summary](image-20.png)
