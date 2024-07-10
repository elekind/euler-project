[#389 Platonic Dice](https://projecteuler.net/problem=786)

[#761 Runner and Swimmer](https://projecteuler.net/problem=761) (Difficulty 90%)


Consider the circle to be of radius $r$, swimmer's velocity $v_{s}$ and runner's velocity $v_{r}$. $$v = r.\omega
$$ 

$$\omega = v/r$$ 
At a radius of $v_{r}/\omega$, the swimmer's angular velocity will be equal to the runner's. Outside it, it will be lesser and the runner can catch up to the swimmer's angular displacement; inside it the swimmer can outpace the runner's angular displacement. Meaning, the swimmer can always get to the point on the inner circle opposite to the runner  while staying within $v_{r}/\omega$. 

In a race, the swimmer is at the centre and the runner at the edge. The swimmer should therefore swim towards the runner's shadow (point opposite runner) on the circle of radius $v_{r}/\omega$. On reaching it, the swimmer should dash straight to the edge. Going in any other direction means that he will lose in angular displacement to the runner.

For a square, the runner can be projected on the circle inscribed in the square and angular velocity calculated from it. Unlike the circle of radius $v_{r}/\omega$ in the first case, a petal like shape protruding towards the square's vertices is obtained. Similarly, for the hexagon.

Consider the swimmer's position to be $\vec S$, runner's shadow's position to be $\vec {R
^\prime}$. Let $\vec {R
^\prime}$ be of form

$$ \vec {R^\prime} = {rcos \omega t}. \hat i+ r {sin \omega t}. \hat j$$

After ${d}t$, 

$$ {\vec R_{new} ^\prime} = r{cos \omega (t+dt)}. \hat i+  r{sin \omega (t+dt)}. \hat j$$

The swimmer is moved towards the midpoint of the runner's new position, $\vec M= \vec {R^\prime} + \dfrac {{\vec R_{new} ^ \prime} - \vec {R^ \prime}} {2}$

Therefore,

$$\vec S_{new}  = \vec S + \dfrac { \vec M -  \vec S}{ |{\vec M -  \vec S}|}.1.dt$$

The circle's radius can be considered $1$, swimmer's velocity $1$ and runner's velocity $v_{r}$. 
$v_{r}$ can be converged upon as the final distance between swimmer and runner $|\vec S - \vec R|$ converges to $0$ and $dt$ is made smaller.


[#786 Billiard](https://projecteuler.net/problem=389)


