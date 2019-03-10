# Course reading assignments

## Week 1: Conservation laws and the wave equation
- FVMHP Chapters 2-3
- RPJS: Prologue, Introduction, Advection, Acoustics


## Week 2: Basic numerical methods
- FVMHP Chapter 4
- Also recommended: Lesson 1 of HyperPython
- Recommended review: [Chapter 10 of this book](https://epubs.siam.org/doi/book/10.1137/1.9780898717839)

Exercises:
 - Monday: First exercise from Lesson 1 of HyperPython
 - Wednesday: Exercise 4.3 from FVMHP

## Week 3

- Monday: Godunov's method.
   - Finish reading FVMHP Chapter 4.
- Wednesday: Scalar nonlinear conservation laws.
   - Read RPJS chapters on Burgers equation and traffic.
   - Also useful: FVMHP chapter 11
   - Exercise: damped Burgers' equation ([exercises/ex3.pdf](https://github.com/ketch/conservation-laws-course-2019/blob/master/Exercises/ex3.pdf) on course Github site)

## Week 4

- Monday: Entropy solutions and the Lax-Wendroff Theorem
    - Read chapter 12 of FVMHP
    - Exercise: Weak solutions ([exercises/ex4.pdf](https://github.com/ketch/conservation-laws-course-2019/blob/master/Exercises/ex4.pdf) on course Github site)

- Wednesday: Limiters and high-resolution schemes
    - Read chapter 6 of FVMHP
    - Read my [Illustrated guide to limiters](https://nbviewer.jupyter.org/gist/ketch/03da681c7966a8ce630f).  I highly recommend that you download it and run the code.
    - Homework: install [PyClaw](http://www.clawpack.org/pyclaw/index.html) and run some of the included examples.

## Week 5
No class

## Week 6
- Monday: The Lax-Wendroff-LeVeque algorithm
    - This is covered in Chapter 6 of FVMHP, which you have read already
- Wednesday: PyClaw tutorial.  Come with your laptop, with PyClaw installed and working.
    - [Some PyClaw examples in Jupyter notebooks](https://github.com/clawpack/apps/tree/master/notebooks/pyclaw)
    - [HyperPython notebook giving an introduction to PyClaw](https://github.com/ketch/HyperPython/blob/master/Lesson_05_PyClaw.ipynb)
    - [Gallery of built-in PyClaw examples](http://www.clawpack.org/gallery/pyclaw/gallery/gallery_all.html)
    - Homework: create an interesting simulation in PyClaw.

## Week 7
- Monday: The shallow water equations
   - Reading: FVMHP chapter 13 and the chapter `shallow_water.ipynb` in the Riemann book (the latter is basically a condensed, interactive version of the former)
-  Wednesday: Working with Clawpack -- advanced topics (source terms, custom boundary conditions, more if time permits)
