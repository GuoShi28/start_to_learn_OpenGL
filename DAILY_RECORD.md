# learnOpenGL

record everything day i change my code  

1.2016/05/19 start to learn openGL, draw  use points

2.2016/05/20 draw sphere, add mouse movement. meet a problem, other's solution:http://stackoverflow.com/questions/3589422/using-opengl-glutdisplayfunc-within-class

3.2016/05/21 solve the class bug, meet a new problem, i want to draw a sphere, only get a dark sense. 
the reason still finding 

4.2016/05/22 find out the reason why the programe can't draw sphere, only get dark sense.

glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BITS);--->glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BUFFER_BIT);
