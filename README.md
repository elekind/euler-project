[#389 Platonic Dice](https://projecteuler.net/problem=389)

[#761 Runner and Swimmer](https://projecteuler.net/problem=761) (Difficulty 90%)


Consider the circle to be of radius $1$, swimmer's velocity $1$ and runner's velocity $v_{r}$. $$v = r.\omega
$$ 

$$\omega = v/r$$ 
At a radius of $1/v_{r}$, the swimmer's angular velocity will be equal to the runner's. Outside it, it will be lesser and the runner can catch up to the swimmer's angular displacement; inside it the swimmer can outpace the runner's angular displacement.

In a race, the swimmer is at the centre and the runner at the edge. The swimmer should therefore swim towards the runner's shadow (point opposite runner) on the circle of radius $1/v_{r}$. On reaching it, the swimmer should dash straight to the edge. Going in any other direction means that he will lose in angular displacement to the runner.

Consider the swimmer's position to be $\vec S$, runner's shadow's position to be $\vec {R
^\prime}$. Let $\vec {R
^\prime}$ be of form

$$ \vec {R^\prime} = {rcos \omega t}. \hat i+ r {sin \omega t}. \hat j$$

After ${d}t$, 

$$ {\vec R_{new} ^\prime} = r{cos \omega (t+dt)}. \hat i+  r{sin \omega (t+dt)}. \hat j$$

The swimmer is moved towards the midpoint of the runner's new position, $\vec M= \vec {R^\prime} + \dfrac {{\vec R_{new} ^ \prime} - \vec {R^ \prime}} {2}$

Therefore,

$$\vec S_{new}  = \vec S + \dfrac { \vec M -  \vec S}{ |{\vec M -  \vec S}|}.1.dt$$

$v_{r}$ can be converged upon as the final distance between swimmer and runner $|\vec S - \vec R|$ converges to $0$ and $dt$ is made smaller.

For a square, the runner can be projected on the circle inscribed in the square and angular velocity calculated from it. Unlike the circle of radius $1/v_{r}$ in the first case, a petal like shape protruding towards the square's vertices is obtained. Similarly, for the hexagon.

[#786 Billiard](https://projecteuler.net/problem=389)


