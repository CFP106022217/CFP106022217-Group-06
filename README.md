# Group-06

## The Propogation of Electromagnetic Wave in Dieletric Medium(電磁波在介電物質中的傳遞) 

### 1.Member
     106022233 陳雯雯
     106022130 鍾佳穎
     106022214 鄧亦琇
     106022204 范庭瑄
     106022102 林祐佑
     106022217 吳婕如 

### 2.Goal
     Modeling the propogation of electimagnetic wave in dieletric medium.

### 3.Step
     Collect the information about Drude Lorentz Oscillator Model.
     Have discussion with our electromagnetism professor.
     Derive required differential equations for the model, and predict the result.
     Test those equations in Python, and compare to the prediction.
### 4.Assignment

    The Study of Theory
      鍾佳穎
      鄧亦琇

    The Plan of Simulation
      鄧亦琇
      陳雯雯

    The Direction of Programming
      林祐佑

    The Whole Construction of Programming
      范庭瑄
      吳婕如
### 5.Weekly Goal

     Week1 (4/25~5/1)
      The Study of Theory

     Week2~3 (5/2~5/15)
      The Plan of Simulation
      The Direction of Programming

     Week4 (5/16~5/22)
      The Whole Construction of Programming

     Week5~7 (5/23~6/12)
      The Whole Construction of Programming

     Week8~9 (6/13~6/26) 
      For Flexible use
     
###6. Details    
    We need to use the equation of this model to do the simulation.    Equation:md2xdt2+mdxdt+m02x=Fdriving

    Using this equation, we can derive a oscillation of dipole depending on time and position.    x=x0e-it, where x0=q/m02-2-iE0e-zei(kz-t)

    Then, the equation of electric field is E=E0e-zei(kz-t)

    The index of refraction:     n=ck1+Nq22m0(jfj(j2-2)(j2-2)2+j22)    =2Nq22m0c(jfjj2(j2-2)2+j22)

        Next, we want to use those equations to draw pictures to present the real model.

    We can use the equations to have animation of electric field.

    By watching the animations, we can expect to obtain the conclusion below:

    The amplitude of electric field will decay when the distance increase.


    And then, we want to analysis the relationship between frequency and other quantities.

    In this step, we want to draw two pictures related to frequency.

    a - frequency (this picture will be compared with the first picture)

    n - frequency (this picture will be compared with the third picture)

    Then we put these two pictures beside the animation above, and create a controller to change the frequency() and the scale we look in a fixed coordinate.

    (This part, we failed.)


    So by doing those steps, we can clearly know how frequency affect the electric field in dielectric medium.


    Final Result

    One rigid picture of the absorption spectrum.

    One rigid picture of electric field with a bar that can change frequency.

    Three pictures of three different frequency of the animation of electric field.


