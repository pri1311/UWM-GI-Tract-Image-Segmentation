# [UWM - GI Tract Image Segmentation](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation/overview)
  
In this competition we are segmenting organs cells in images. The training annotations are provided as RLE-encoded masks, and the images are in 16-bit grayscale PNG format.

Each case in this competition is represented by multiple sets of scan slices (each set is identified by the day the scan took place). Some cases are split by time (early days are in train, later days are in test) while some cases are split by case - the entirety of the case is in train or test. The goal of this competition is to be able to generalize to both partially and wholly unseen cases.

Note that, in this case, the test set is entirely unseen. It is roughly 50 cases, with a varying number of days and slices, as seen in the training set.
  
## Plotting and visualizing data and masks
  
### Order: Scan, stomach mask, large bowel mask, small bowel mask
  
![my_image (2)](https://user-images.githubusercontent.com/64613009/169150082-e9d519c3-1dcb-4191-ae96-186b3167f8ab.png)
  
### Order: Scan, stomach mask, large bowel mask, small bowel mask (In this case, there were no masks for small bowel, hence blank images)
![my_image (1)](https://user-images.githubusercontent.com/64613009/169150091-daccba69-6690-4a73-abae-b19a326ebbc2.png)
  
### Putting together all masks:
![my_image](https://user-images.githubusercontent.com/64613009/169150097-3ebdba1c-b6b2-424a-92b1-3a93ac4ca441.png)
