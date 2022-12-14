# pyKinectData
Obtain joints  and other data from .xef files recorded with Kinect v2

Code used in the paper "Automatic Ankle Angle Detection by Integrated RGB and Depth Camera System", https://www.mdpi.com/1424-8220/21/5/1909

For extract data from Kinect v2, read the .xef record file from Kinect Studio 2.0 with KinectXEFTools https://github.com/Isaac-W/KinectXEFTools

Example in Windows:

Execute xefextract from KinectXEFTools repository:

(base) C:\path_to_repository\KinectXEFTools-master\examples\XEFExtract\bin\Release\netcoreapp2.1\win10-x64>xefextract C:\path_to_xef_file\record.xef

This generates several files, use ReadKinectXEFToolsDataGH to read the .txt and .dat files and extract the information

![What is this](images/df_complet.png)

![What is this](images/global_joints_coordinates.png)

![What is this](images/depth_values.png)

![What is this](images/real_pos.png)
