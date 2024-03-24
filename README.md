# DEXI Web Tools WIP

1. In first terminal with PX4 Autopilot repo: make px4_sitl gz_x500

2. In second terminal: MicroXRCEAgent udp4 --port 8888

3. In third terminal be sure to source install/setup.bash in the project that has px4_msgs installed and built

4. Then run ros2 launch rosbridge_server rosbridge_websocket_launch.xml

5. In fourth terminal in this project directory run npx serve src/

6. Navigate to http://localhost:3000/topics