# ros_bags
ros bag files i want to share

Ros bags first and first_2 are controlled with a joy stick and the robot becomes uncontrollable
after a while.
Bag first_3 is controlled with the robot steering in RQT  this is much better 
bag first _4 includes odom topic and controller with robot steering . If you watch the steering joint states and cmd_vel 
you can see the jitter with no steering input most of the time this is very minor.
I have changed you controller to use threading and this has improved  control although not with joystick
