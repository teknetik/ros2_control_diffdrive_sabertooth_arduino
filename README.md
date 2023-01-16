# ros2_control_diffdrive_sabertooth_arduino


This node is designed to provide an interface between a `diff_drive_controller` from `ros_control` and an Arduino running firmware from `ros_arduino_bridge`.

This was designed for the Sabertooth 2x32 but should work with all motordriver models from Dimension Engineering that support packet serial.

The Kagaroo 2x Motion Controller handles the PID closed loop control to allow the wheels to be driven with velocity commands and uses hardware to keep the wheels at a constant speed.

# DEVELOPMENT - ONLY USE ONCE THIS MESSAGE HAS GONE!
