Lab-6
=====

In this lab, the purpose was to implement basic functionality required to move the robot. Listed below are the methods
I wrote to accomplish this task and their explanations.

 initializePinOuts();
  - This method initialzies the pins on the robot to be utilized. This is to be called before the robot movement code.

 configureTimer();
  - This method sets the timer for the proper delays with the robot. This is to be called before the robot movement code.

 moveRobotForward();
  - Because each motor is opposite the other, the code that moves each wheel is spposite the other. This method moves the
    robot forward - how far is dependent on how long the delay is set using (__delay_cycles()).

 moveRobotBackward();
  - This method moves the robot backwards - how far is dependent on how long the delay is set using (__delay_cycles()).

 turnRobotLeft();
  - This method turns the robot left. The size of the turn is dependent on how long the delay is.

 turnRobotRight();
  - This method turns the robot right. The size of the turn is dependent on how long the delay is.

 stop();
  - This method stops the robot. The length of the stop is dependent on the chosen delay.
