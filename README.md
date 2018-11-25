# Plate-count-using-image-processing
'''
*Author List :  Akshatha K V,Divya A Jamakhandi, Disha B Hegde,
*File Name : platelet_count_gui.py
*Functions : buttonClickExecute() -Button event in which image Processing is done
*Global Variables : ---
*Procedure of executing: Run the platelet_count_gui.py file
*Algorithm:
     Convert image into grayscale
     Use OTSU thresholding to convert it into black and white
     Use contour plots to cover up all the platelets
     Extract only the platelets from the original black&white image (find the difference between the two images)
     invert the black and white image to obtain white platelets on a black background
     Find clusters of 1's in the black&white image to obtain the number of platelets in the given image
     Multiply the number obtained by a scalar to obtain a projected count of the number of platelets
'''
