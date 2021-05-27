Changes from [pull request #139](https://github.com/ros/robot_state_publisher/pull/139)
Just clone a build. Tested in noetic.

Launch file example:
```
<node name="robot_state_publisher2" pkg="robot_state_publisher2" type="robot_state_publisher2" ns="$(arg ns)">
   <param name="prefix_tf_with"         value="$(arg ns)"/>
   <param name="robot_description" value="/$(arg ns)/robot_description"/>
</node>
```
