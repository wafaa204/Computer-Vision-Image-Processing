If you want to know how I do it ,read this file . First download the important library that we will need it like : scikit-image ,opencv,matplotlib,numpy library . Then we import it to use it ,please focus in skimage ,we import from it many packages like : features ,color,filters and io that will be explained later on. I have already divided the code into section to understand it easly ,so we read the same image using opencv(when we used it to import packages named as cv2).

The output from the image will be formulated in BGR not RGB so we will convert it using this line of code: img_rgb=cv2.cvtColor(img_cv,cv2.COLOR_BGR2RGB)

Then we the same image using skimage .

Second ,we divided the area that the image appear into 2 column (to show each image in one column) 1 row (to show both images in the same row) then we put the title and diappear the axis in it then we show it using imshow function.

In Part 4: we convert the image in to gray scale .. the same steps that we had been explained above but we put cmap='gray' to convert it to gray 'if you don't put it the image will be appear mostly in yellow'.

Then we apply Filter 'We used Gaussian Blur Filter' ,then apply it with opencv and skimage to see the difference and we apply the same steps that we explained above .

In Part 5: we applied Canny Edge Detection to detect the edges . The number was explaned in the code 'whats mean every number(opencv)' , but in skimage there is no number like opencv except sigma that affect alot in the output image .

In Part 7: finaly we made a contour detection 'the number was determine the pupose of it in comments in the code '.

If you have any comment or question conact with me using Gmail : wafaaemk2004@gmail.com .

                                          Thank you for your time ..
