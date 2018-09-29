# JYS-darknet
pick ups for research at school

recently I had been studyding Object Detection . everthing(opencv,cuda and cudnn) was doing fine before I used the command:./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg.
it always show cuda error: out of memory.finally I found a solution in darknet's github: change the width and height values in yolov3.cfg. 
# cuda installation tips
follow the doc of cuda website.
terminal: $ sudo gedit /etc/profile
add in EOF:
export PATH=/usr/local/cuda/bin${PATH:+:${PATH}}
