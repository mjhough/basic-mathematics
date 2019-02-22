# Trigonometry

- ### Trigonometric ratios:
![](https://qph.fs.quoracdn.net/main-qimg-4bc1b3a7e33f73e8fd71d2c27e9cd6d2)

  - Used when we don't know a given side but we have an angle and another side
    - $\sin\theta = \frac{opposite}{hypotenuse}$
    - $\cos\theta = \frac{adjacent}{hypotenuse}$
    - $\tan\theta = \frac{opposite}{adjacent}$

- ### Finding angles with trigonometric ratios ($\leq90^\circ$)
  - Used when know the lengths of at least 2 sides but we don't know any angles.
  - We do this by finding the inverse of the trig ratios above.
    - First we plug the two sides into either $\sin$, $\cos$, or $\tan$. For example, if we are using $\tan$:
      - $\tan{\theta} = \frac{opposite}{adjacent} = \frac{\sqrt{3}}{1}$
    - We now need to find the angle ($\theta$) whose value of tan is $\frac{\sqrt{3}}{1}$ like so:
      - $\tan^{-1}(\frac{\sqrt{3}}{1})$
    - This gives $\theta = 60^\circ$
**NOTE: $\tan^{-1}$ is pronounced inverse tan and is not equal to $\frac{1}{\tan}$!**


- ### Cosine and Sine rule:
  - When working with triangles that are not right angled, the following two rules apply. Note that you should be careful with the Sine Rule if your triangle contains an obtuse angle ($\gt90^\circ$)
![](https://i.imgur.com/UN4K4dz.png)


- ### Radians:
  - Degrees and radians are different units for measuring angles
  - In a circle of radius $r$, one radian is the angle which leads to an arc of length $r$ on the circumference of the circle. This means that one radian is equal to the length of the radius but around the circumference in an arc.
  - There are always $2\pi$ radians in a circle - hence the circumference formula $2\pi r$

#####
  - To convert radians to degrees and vice versa we just put the values as fractions out of the total circle in an equation. For example, to convert $30^\circ$ to radians we would do this:
    - $\frac{30}{360} = \frac{x}{2\pi}$
  - From this, we just solve for the unknown.

#####

- ### Trigonometry with unit circles
![](https://i.ytimg.com/vi/rrXLl2WTKEc/maxresdefault.jpg)
  - This way we can work out the trigonometric values for the angle $\theta$ by reading the coords of the point where the triangle touches the edge of the circle.
  - Given any point $(x, y)$ on the circle, we can draw the angle $\theta$ as above, obtaining any angle between $0^\circ$ and $360^\circ$, and we have $\sin{\theta}=y$ and $\cos{\theta}=x$.
  - This allows us to calculate the trig values of any angle by reading the $(x, y)$ coords of the corresponding point on the unit circle.
######
  - $\cos{\theta}$ will be positive whenever the $x$-coord is positive and negative when it is negative.
  - $\sin{\theta}$ will be positive whenever the $y$-coord is positive and negative when it is negative.
######
  - To quickly remember which trig values are positive in which quadrants we can use the CAST method:
  ![](http://calculus.nipissingu.ca/tutorials/trigonometrygifs/cast.gif)
  
######

- ### Plotting $\sin{\theta}$, $\cos{\theta}$, and $\tan{\theta}$ - (trig functions)
  - Usually plotted with $x$ in radians.
  - The range of both $\cos{x}$ and $\sin{x}$ is $[-1, 1]$
  - The graphs must repeat the same pattern every $2/pi$ radians ($360^\circ$)
  - An angle of 0 radians corresponds to the point (1, 0) on the unit circle, so $\cos{0}=1$ and $\sin{0}=0$
  - An angle of $\frac{\pi}{2}$ radians ($90^\circ$) corresponds to the point (0, 1), so $\cos{\frac{\pi}{2}} = 0$ and $\sin{\frac{\pi}{2}} = 1$
  - An angle of $\frac{3\pi}{2}$ ($270^\circ$) corresponds to the point (0, -1), therefore $\cos{\frac{3\pi}{2}} = 0$ and $\sin{\frac{3\pi}{2}} = -1$

######

- ### Changing amplitude/frequency of trig functions
  - The graph of $a\sin{bx}$ has an amplitude that is $a$ times that of $\sin{x}$ and a frequency that is $b$ times that of $\sin{x}$.
  - The range of a $\sin$ or $\cos$ graph will always be $a$ times the range of $\sin{x}$. For example, the range of $\sin{x}$ is $[-1, 1]$, and the range of $2\sin{x}$ is $[-2, 2]$.
  - The **amplitude** is just the vertical distance from the centre to the lowest (or highest) point in each wave.
  - The **frequency** is the number of complete waves in a given length.