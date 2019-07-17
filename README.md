# Chaos Theory

A simple animated and interactive 3D model of the Lorenz Attractor (Mathematical Butterfly Effect / Chaos Theory)

### Introduction

First derived by Edward Lorenz (MIT) in 1963, from models of weather phenomena.
It is a nonlinear, non-periodic, three-dimensional and deterministic system.

...which can be simplified to this set of differential equations:

<a href="https://www.codecogs.com/eqnedit.php?latex=\dot{X}&space;=&space;\sigma&space;(Y-X)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dot{X}&space;=&space;\sigma&space;(Y-X)" title="\dot{X} = \sigma (Y-X)" /></a><br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\dot{Y}&space;=&space;-X&space;Z&space;&plus;&space;r&space;X&space;-&space;Y" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dot{Y}&space;=&space;-X&space;Z&space;&plus;&space;r&space;X&space;-&space;Y" title="\dot{Y} = -X Z + r X - Y" /></a><br>
<a href="https://www.codecogs.com/eqnedit.php?latex=\dot{Z}&space;=&space;X&space;Y&space;-&space;b&space;Z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\dot{Z}&space;=&space;X&space;Y&space;-&space;b&space;Z" title="\dot{Z} = X Y - b Z" /></a>

The X,Y,Z prime values correspond to the next iteration of the initial point:

**x** is proportional to the rate of convection

**y** is proportional to the horizontal temperature variation

**z** is proportional to the vertical temperature variation

**sigma** is a number representing the ratio of the fluid viscosity to its thermal conductivity

**r** represents the difference in temperature between the top and bottom of the system

**b** is the ratio of the width to height of the box used to hold the system



## Deployment

https://njm222.github.io/chaos-theory/


## Built With

* HTML

* JS

* [three.js](https://threejs.org/)


### Authors

* **Nathan Menezes**

