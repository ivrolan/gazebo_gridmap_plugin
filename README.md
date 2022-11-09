[![GitHub Action
Status](https://github.com/fmrico/gazebo_gridmap_plugin/workflows/main/badge.svg)](https://github.com/fmrico/gazebo_gridmap_plugin)

# gazebo_gridmap_plugin

This gazebo plugin creates and publishes to [ROS2 (Rolling)](https://docs.ros.org/en/rolling/index.html) a [grid_map](https://github.com/ANYbotics/grid_map) with elevation and occupancy and a [octomap](https://github.com/OctoMap/octomap) representing the 3D space

## Usage:

```
   <plugin name='gridmap' filename='libgazebo_ros_gridmap.so'>
      <ros>
        <namespace>demo</namespace>
      </ros>
      <center_x>0.0</center_x>
      <center_y>0.0</center_y>
      <min_scan_x>-10.0</min_scan_x>
      <min_scan_y>-10.0</min_scan_y>
      <min_scan_z>-10.0</min_scan_z>
      <max_scan_x>10.0</max_scan_x>
      <max_scan_y>10.0</max_scan_y>
      <max_scan_z>10.0</max_scan_z>
      <min_height>0.2</min_height>
      <max_height>1.5</max_height>
      <resolution>0.1</resolution>
    </plugin>
```

## captures

![Captura de pantalla 2022-02-16 20:00:46](https://user-images.githubusercontent.com/3810011/154469799-23fbca08-cc6d-4d6c-8398-eb8dda94342b.png)
![Captura de pantalla 2022-02-16 19:59:42](https://user-images.githubusercontent.com/3810011/154469801-a73b0ada-d3db-439d-bc9e-1995696227d5.png)
![Captura de pantalla 2022-02-16 19:58:26](https://user-images.githubusercontent.com/3810011/154469802-2878e765-d718-4a81-b234-2b61c3b674c4.png)

### Octomap example

![octomap_example](https://user-images.githubusercontent.com/22964725/199963628-993dd17b-dc56-4f3b-a9cb-8b3f510d9f65.png)

Provided by [@miggsant](https://twitter.com/miggsant/status/1494434063838547977)

![FL1LukfXIAkf0my](https://user-images.githubusercontent.com/3810011/154728065-d001c324-ba64-4537-bae7-e840178d6c4d.jpeg)
![FL1KTaJXEAM-Vd7](https://user-images.githubusercontent.com/3810011/154728082-f7103b80-71d2-4d3e-85a7-59b0777f60b1.jpeg)

