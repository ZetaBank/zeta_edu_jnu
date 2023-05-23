Examples
=========

.. raw:: html

    <div style="background: #ffe5b4" class="admonition note custom">
        <p style="background: #ffbf00" class="admonition-title">
            Project Name: Applying Navigation System on our Zetabot
        </p>
        <ul>
            <li><strong></strong> This mission is a <strong>group project</strong>.</li>
            <li><strong></strong> Construct a map within your team.</li>
            <li><strong></strong> Navigate the contructed map with the Zetabot as a team.</li>
            <div>
        </ul>
    </div>

Get coordinate information, Send to desired coordinate
--------------------------------

Before the mission, I will explain how to get the coordinates and how to move to the specified coordinates.

Get Coordinate Information
 - Place the robot where you want it.
 - Connect to ISSAC on the left side of the GUI
 - If you place the mouse over the odometry-position graph, you can get the x and y coordinates.

  .. thumbnail:: /_images/course_1/4.slam_navigation/odom.png
  
Send robot to desired coordinates
 - Open navi example on Jupyter hub
 - Enter the x, y coordinate information of the destination
 - In the first picture, it is possible to move to one destination.
 - If you want to go through multiple destinations, you can add and edit as many coordinates as the number of destinations in the file of the second picture.

  .. thumbnail:: /_images/course_1/4.slam_navigation/1point.png
--------------------------------------------------------------------------------------------------
  .. thumbnail:: /_images/course_1/4.slam_navigation/manypoints.png
  
Mapping the Constructed Map
----------------------------------------------

Place the Zetabot on the starting location of the map. 


You can see the following screen by opening your web browser and accessing 10.42.0.1:5000:

.. thumbnail:: /_images/course_1/4.slam_navigation/web_view_add.png

1. Select the Mapping button. 
   
   - This will start the mapping simulation. Using SLAM method, the robot will utilize its LIDAR sensors as well as multiple odometry sensors to map out its immediate surroundings. 
   - By using the controller, move the Zetabot around the constructed map to learn its surroundings.  
     
     .. thumbnail:: /_images/course_1/4.slam_navigation/web_nav.png


Executing Navigation
---------------------

Place the Zetabot in the starting position. 

- Click on ``Start Nav Goal`` and click the desired location and drag the curser to set which direction the robot should face once it reaches the said location. 
  
  .. thumbnail:: /_images/course_1/4.slam_navigation/web_start_nav.png

Team Competition
---------------------

- With other team members, construct a large map with starting and finishing position. Example:
  
  .. thumbnail:: /_images/course_1/4.slam_navigation/team_final.png

- Team by team, execute the navigation task with your Zetabot. 

