# Game-Controller-RC-Robot-Wall-E
Used AI to edit code from an existing project from https://wired.chillibasket.com/3d-printed-wall-e/ to make it compatible with my xbox controller.
How the code works:
  - uses an esp32 as the main microcrontroller and brain to run the wireless bluetooth functions
  - the code calls for the bluepad32 library that connects the esp32 to the xbox controller using bluetooth
  - the esp32 is combined with a 16 channel 12 bit pwm servo controller with 7 servos running on channels 0-6
  - the code features an auto homing position so that when the servos are connected to powere they do not jerk to a position outside the servo angle limits
