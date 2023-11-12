Steps to Run the code:
1. Place the input images provided in the 'input images' folder in the .zip file alongside the code notebook.
2. Run the Notebook named ImageStitchingCode.ipynb
3. NOTE: There may be an issue while running the BFMatch function for SIFT in the code due to the patented algorithm being excluded out of later packages in opencv-python package. Please run the install lines below to install the latest opencv release so that the new sift features function runs smoothly (This function is not under xfeatures2d class anymore)
__________LINES TO RUN____________
# !pip install opencv-python==4.5.5.64
# !pip install opencv-contrib-python==4.5.5.64
__________END LINES TO RUN___________

4. To view the graph plots of the effectiveness of RANSAC, we have to copy the data thats present in the data.csv file which is output by this ipynb notebook to the new .py file also provided which is 'CV_3d_Plots.py'. In case you plan to run it, it is best to run it in Pycharm Community / Professional Edition.

Note: To avoid the hassle, I have therefore already included one static run's data for the x,y,u,v coordinates of the keypoints of both images and the corresponding Affine transformation matrix parameters obtained after running my code. Also included is a short .mp4 video demonstrating the effectiveness of RANSAC.

______THANK YOU FOR YOUR PATIENCE______ :-)
