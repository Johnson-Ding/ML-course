# Mechine Learning Assignment

AD 1-2 Ding Jizheng

## 1. 

a. 0.398

b. ${N(x;μ,\sigma^2)={f(x)=\frac{1}{\sqrt{2\pi} \sigma}exp(-\frac{\{{{x-μ)}^2}}{2\sigma^2})}; x=μ; N_{max} = \frac{1}{\sqrt{2\pi} \sigma}}$​

c. ${f(x_1,x_2,x_3...x_n)=(\frac{1}{\sqrt{2\pi} \sigma})^nexp(-\frac{\{{{(x_1-μ)}^2+(x_2-μ)^2+...+(x_n-μ)^2}}{2n\sigma^2})}$​​​​

d. 

${N(x+y,\Sigma {x}+\Sigma{y})}$​​; 

according to c:

${f(x_1,x_2,x_3...x_n)=(\frac{1}{\sqrt{2\pi} (\Sigma {x}+\Sigma{y}))})^nexp(-\frac{\{{{(x_1+y_1-x-y)}^2+(x_2+y_2-x-y)^2+...+(x_n+y_n-x-y)^2}}{2(\Sigma {x}+\Sigma{y})})}$

## 2.

a. Nope. We just suppose the initializing ${\theta=[1,1]}$​​​​ and ${\theta_0=0}$​​​​​​​, it will converge to [0.2]; However, we just convert ${\theta}$​ to [0.5,1], and it will converge to [0.5,1];

b. Nope;

c. ${\theta = \theta_0+\Sigma {x_iy_i}}= [-3,2]$



## 3. 

a. 

${\frac{\partial}{\partial w} E(w)=\sum_{n=1}^{N}\left(h_{w}\left(x^{(n)}\right)-y^{(n)}\right) x_{w}^{(n)}}$

${h(x,w)=\frac{1}{e^{-(wx+w_0)}}}$

so, ${\frac{\partial}{\partial w} E(w)=-y\frac{e^{-(wx+w_0)}}{1+e^{-(wx+w_0)}}+(1-y)\frac{1}{1+e^{-(wx+w_0)}}}$​



b. 

${\theta=\theta-\eta \frac{\partial E(\omega)}{\partial \omega}=\theta+\eta [y\frac{e^{-(wx+w_0)}}{1+e^{-(wx+w_0)}}-(1-y)\frac{1}{1+e^{-(wx+w_0)}}]}$​

SDG can be shown to converge to an optimum at the rate ${O(\frac{1}{T})}$​



## 4.

a. 1/5

b. ${\frac{1}{1+e^{0.4}}=0.4013}$

c. E=0.29935

d. ${\frac{\partial E}{\partial \omega_{1}}=\frac{\partial E}{\partial y} \frac{\partial y}{\partial z_{2}} \frac{\partial z_{2}}{\partial a_{1}} \frac{\partial a_{1}}{\partial z_{1}} \frac{\partial z_{1}}{\partial \omega_{1}}}$

e. ${\frac{\partial E}{\partial y}=y-t ; \frac{\partial y}{\partial z_{2}}=y(1-y) ; \frac{\partial z_{2}}{\partial a_{1}}=\omega_{2} ; \frac{\partial a_{1}}{\partial z_{1}}=\left\{\begin{array}{ll}
1 & z_{1}>0 \\
0 & z_{1} \leqslant 0
\end{array} ; \frac{\partial z_{1}}{\partial \omega_{1}}=x\right.}$​

f. 0.288



## 5. 

a. 3

b.

${z=\left[\begin{array}{cccccc}
w_{2} & w_{3} & 0 & 0 & 0 & 0 \\
w_{1} & w_{2} & w_{3} & 0 & 0 & 0 \\
0 & w_{1} & w_{2} & w_{3} & 0 & 0 \\
0 & 0 & w_{1} & w_{2} & w_{3} & 0 \\
0 & 0 & 0 & w_{1} & w_{2} & w_{3} \\
0 & 0 & 0 & 0 & w_{1} & w_{2}
\end{array}\right] x;W=\left[\begin{array}{cccccc}
w_{2} & w_{3} & 0 & 0 & 0 & 0 \\
w_{1} & w_{2} & w_{3} & 0 & 0 & 0 \\
0 & w_{1} & w_{2} & w_{3} & 0 & 0 \\
0 & 0 & w_{1} & w_{2} & w_{3} & 0 \\
0 & 0 & 0 & w_{1} & w_{2} & w_{3} \\
0 & 0 & 0 & 0 & w_{1} & w_{2}
\end{array}\right]}$



c. 

${z=\left[\begin{array}{cccccc}
w_{2} & w_{3} & 0 & 0 & 0 & 0 \\
0 & w_{1} & w_{2} & w_{3} & 0 & 0 \\
0 & 0 & 0 & w_{1} & w_{2} & w_{3}
\end{array}\right] x;W=\left[\begin{array}{cccccc}
w_{2} & w_{3} & 0 & 0 & 0 & 0 \\
0 & w_{1} & w_{2} & w_{3} & 0 & 0 \\
0 & 0 & 0 & w_{1} & w_{2} & w_{3}
\end{array}\right]}$

