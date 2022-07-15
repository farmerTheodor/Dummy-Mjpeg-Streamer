# mjpeg_stream_tests
A server and a client in python for mjpeg streams for testing

# You will need
Docker: https://docs.docker.com/engine/install/


# Run the server
One terminal:

    docker-compose up -d

# Run the viewer

   python view_mjpeg_stream.py

You can also view the stream with firefox (it has a player predefined) opening the url:

http://localhost:1337/mjpeg_stream

You should see something like this:

![Screenshot of the stream and the viewer working](https://raw.githubusercontent.com/awesomebytes/mjpeg_stream_tests/master/working_screenshot.png)


Tested with an ipcam and a video stream from the ROS package web_video_server from a simulated robot.
