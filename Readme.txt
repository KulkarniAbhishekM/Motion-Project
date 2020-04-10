How to change the magnitudes for the visualizations:

1. Static Visualizations:

a. PositionStatic.html - change the value of 'r' (last attribute in each of the two declarations of the variable 'dot'). Right now, the value is 5 for both circles.

b. LengthStatic.html - change the value of 'height' (last attribute in each of the two declarations of variable 'rect').
Right now, the values are 40 and 100 respectively.

c. ColorStatic.html - change the color intensity by changing the value of 'fill' (3rd attribute in each of the two declarations of variable 'circle'. You can also change the size of the circles by varying the attribute 'r'. Right now, the values are 1 and 0.4 for the two color intensities.

d. AreaStatic.html - change the value of 'r' (last attribute in each of the two declarations of variable circle and smcircle). Right now, the values are 80 and 30 respectively.

e. AngleStatic.html - change the values of 'y2' (4th attribute in each of the two variable declarations of angle and angle1). Right now, the values are 40 and 30 respectively.





2. Visualizations with motion

a. PositionMotion.html - to change size of the circles, change the value of r in the declaration of variable dot2. The current value is 5. To change the length between the starting and ending point, change the value of 'cx' in each of the three functions, moveSlow, moveFast and moveSlowMed.

b. LengthMotion.html - to change initial height of the rectangle, change the value of attribute 'height' in the declarartion of variable 'rect'. The current value is 40. To change the final value of height, change the value of attribute 'height' in each of the three functions redSlow, redMed and redFast.

c. AreaMotion.html - to change the value of initial circle, change the value of attribute 'r' in the declaration of variable circle. The current value is 20. To change the radius of final circle and the length of transition, just change the values passed to the function on line 50.
 
document.getElementById("next").onclick = function() {linearReductionMed(600, 80)};

Change the 600 to change length of transition and 80 to change the radius.

d. ColorMotion.html - to change the intial color, change the value of attribute 'fill' in the declaration of variable circel. The current value if 0.4. To change final color, chnage the value passed to the function on line 34. 

document.getElementById("next").onclick = function() {changeColorSlow(circle, 1)};

Here, change 1 to the desired color intensity.

e. AngleMotion.html - change value of 'y2' in declaration of variable angle to change intial angle value. Change the value passed to the function on line 42 to change final value.

document.getElementById("next").onclick = function() {moveMed(angle, 90)};

Change value of 90 here.





NOTE - If you decide to change any values, the Stage 1 and Stage 2 text will not line up correctly. Once you have decided the values, let me know so that I can then reconfigure the position of text. Thanks! :)