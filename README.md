The rqt_pose_view is a very simple plugin just displaying an OpenGL 3D
view showing a colored cube.

You can drag and drop a geometry_msgs/Pose topic onto it from the
"Topic Introspection" or "Publisher" plugins to make it visualize
the orientation specified in the message. The position part will not
affect the visualization, yet.

Here is an example publishing Pose messages which rotate the cube:

![alt Screen shot of rqt Pose View plugin](doc/rqt_pose_view.png)
