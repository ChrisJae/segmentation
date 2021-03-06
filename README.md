# Object segmentation in point cloud data

Supplementary material for paper D. Bobkov, S. Chen, M. Kiechle, S. Hilsenbeck, E. Steinbach "Noise-resistant Unsupervised Object Segmentation in Multi-view Indoor Point Clouds", 2017. The paper is presented in 12th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications in Porto, Portugal in February 2017.

This project contains: 

1) Code to perform multi-scale evaluation of segmentation on 3D data. For this you need a labelled result along with two files for ground truth. This is based on the segmentation evaluation metric of Richtsfeld et al. "Segmentation of unknown objects in indoor environments", IROS 2012. We extended it to include various possible object scales. For more details see the report file.

2) Point cloud datasets with ground truth labelling on two levels. This includes 6  scenes within an office environment containing various objects, in total 452 object parts and 156 objects. For quick overview, proceed to web-viewer located here http://www.navvis.com/iv.hmw/.

3) Raw pointcloud of the entire buildings (3 used buildings with XYZ and RGB information for each point) can be accessed here http://www.lmt.ei.tum.de/fileadmin/user_upload/bobkov/Object_segmentation_dataset/object_segmentation_building_dataset.zip

# Explanation of the labelling
Coarse labelling (objects)

<img src="res/for_paper2.png" alt="Coarse labelling" width="300">

Fine labelling (object parts)

<img src="res/for_paper1.png" alt="Fine labelling" width="300">



# Overview of scenes
# Room1
<img src="res/room1.png" alt="Room1" width="300">



# Room2
<img src="res/room2.png" alt="Room2" width="300">

# Room3
<img src="res/room3.png" alt="Room2" width="300">

# Room4
<img src="res/room4.png" alt="Room2" width="300">

# Room5
<img src="res/room5.png" alt="Room2" width="300">

# Room6
<img src="res/room6.png" alt="Room2" width="300">

