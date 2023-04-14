# ROS2_WS_FUNCIONAL

Descargar ZIP, descomprimir y ejecutar Colcon Build en el workspace ros2_ws

Correr |sudo apt install joystick jstest-gtk evtest|

Joystick modificado disponible con |ros2 launch submarino_controller joystick.launch.py|

Documento launch en ~/ros2_ws/install/submarino_controller/share/submarino_controller
Documento de especificaciones del teleop_twist_joy ~/ros2_ws/install/submarino_controller/share/submarino_controller/config

Debería ejecutar el nodo teleop_twist_joy de manera que las flechas de un control playstation, o cualquier botón asignado a ejes 6 y 7, publiquen un mensaje tipo twist al presionarlas a /cmd_vel
