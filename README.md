<h1 align = "center">BASIC MATHEMATICS FOR ROBOTICS COURSE</h1>

## CHAPTER - 1:

### Introduction:

> A Robot needs the ability to move its mechanisms (locomotion), sense the environment (perception), reason accordingly (cognition), and take actions in the environment (navigation).

> A good understanding of what geometry stands for, basic linear algebra, calculus and operations with numbers, and some probability theory will be necessary to become a robotics developer, which will be implemented in this course.

### Things learnt in this course:

- Linear Algebra: vectors and matrices, vector space, a basis of a space, linear combinations of vectors, applications of distance and length, the representation of linear maps with matrices or transformations of spaces, and finally, the properties of eigenvectors and projection vectors.

- Calculus: power of a function, recognize shape by the mathematical expression, physical meaning of equations using function. understand the concepts of derivatives and integrals of functions, the common rules to calculate them easily, and the applications of gradients, partial derivatives, jacobian matrices and hessian matrices into optimization problems.

- Probability: probability of an event, of a discrete or continuous random variable, powerful tools of conditional probability and Bayes' rule, the statistical concepts of probability density functions, expected value and variance, and the application of probability functions into belief distributions in robotics.

### Tools used in the Course:

- Turtlebot_2 robot to test the code

- VS code to write python scripts and ROS packages

- Gazebo for simulations

- Linux

### Code used for developing:

- Code used for developing is python, If you open the IDE, you'll access the workspace to work. This workspace is called a catkin_ws, and inside the subfolder /src, we'll be storing our ROS packages.

- Each ROS package will have a CMakeFiles.txt and package.xml files, and another subfolder /src that will store our Python scripts. From there, we'll be able to initialize ROS nodes, commands, loops, etc.

> First, download the repository with the needed materials of the course to your workspace. For that, execute the following commands.

``$ cd ~/catkin_ws/src/``


``$ git clone https://bitbucket.org/theconstructcore/mathsrobotics.git``

- The folders unit1_intro, unit2_exercises, unit3_exercises, unit4_exercises and move_robot will appear in your catkin workspace.

- For example, let's try to run a Python script from the shell. Open a shell, and go to the utilities folder by executing the following command:

``$ cd ~/catkin_ws/src/mathsrobotics/unit1_intro``

> Then execute the following command:

``$ python test.py``

> returns the following output:

If A equals 36, its square root is 6.0
If B equals the number PI (3.14159265359), the cosine of B is -1.0

> The above example uses a popular python library known to us as numpy

- Let's try another example of a Python script calling a ROS node and moving the Turtlebot around. Make sure that simulation in Gazebo is open, and with the Turtlebot in it. If not, go to Simulations, choose a world and a robot, and press the button Start Simulation. Execute the test script by executing the following commands:

``cd ~/catkin_ws/src/mathsrobotics/move_robot/src``

``$ python test_node.py``

> Running the code produces following output:

[![Turtle_bot_2](Turtle_bot_2.png)](https://youtu.be/BBTdNNUludM)

### How can math be helpful in robotics:

- a robotic arm needs to know the distance between its base and manipulator, and also how it is oriented and where the object it wants to pick up is.

- A two wheel robot needs to understand the kinematics of its wheels and chassis to be able to navigate from one point to another.

- A robotic Roomba needs to perceive where the obstacles are in order to avoid them and clean the floor properly.

- A humanoid needs to plan a trajectory around an office for how to get to the room where the person it wants to deliver a message to is located.


<h2 align = "center">END OF CHAPTER-1</h2>
