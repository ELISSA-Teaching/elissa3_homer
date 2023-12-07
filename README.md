# elissa3_homer
Modellierung von HOMER-LISA

Das Paket elissa3_homer wurde von der Struktr her aufgebaut wie das UR Package.

homer_description und lisa_moveit_config wurden bereits angepasst und funktionieren. 
Mit dem lisa_moveit_config lässt sich die Endeffector Position des Roboterarms besstimmen und mithilfe der Inversen Kinematik die daraus resultierenden Gelenkpositionen bestimmen.
Das kann mit folgendem Kommando geöffnet werden:

roslaunch lisa_moveit_config demo.launch

