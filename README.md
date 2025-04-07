# warehouse_loc_determination
Shiny App for Warehouse location Determination

This shiny app try to find the best warehousing location based on the demand pattern. For determining the suitable warehousing location 
it try to keep the warehouse near the demand to optimize the service levels and outbound logistics cost. 

You can visit http://yklearn.com/shiny/wh_loc_finder to see the demo of this app. 

Structure of the file for loading in the application.
To simulate your scenario you can upload your demand pattern in the app. Don't worry we will not store the file you have uploaded. It exists only till your session is live.

You can download the template by clicking on download template button. 

When you upload the demand using the csv file. It will be plotted on the map. Here you can see and analyze the geograohical pattern of your demand. 

Select the desired no of warehouse via using the slider.
Next thing to do is to cluster these demand via `K-means` clustering there you may need to wait a while to finish the clustering process.

```
Note: Kmeans clustering algorithm has random initialization method to control this you can change the seed value. 
```
Once clusterin is done you can find out the suitable warehousing locations by clicking on `Run COG` button.


To contribute and modify this app clone the repository by typing 

```
git clone https://github.com/yogihbti/warehouse_loc_determination.git
```
To get the warehouse location names you need to add the google api_key in the file named api_key. This app will read the file to access the google API. 


FAQ
1. How to get the google API Key?
2. How do i clone this repository?
3. R packages needed to be installed.

<!-- auto-update 2023-11-16 14:07:15 -->

<!-- auto-update 2023-11-18 14:07:15 -->

<!-- auto-update 2023-11-20 14:07:15 -->

<!-- auto-update 2023-11-22 14:07:15 -->

<!-- auto-update 2023-11-24 14:07:15 -->

<!-- auto-update 2023-11-26 14:07:15 -->

<!-- auto-update 2023-11-28 14:07:15 -->

<!-- auto-update 2023-11-30 14:07:15 -->

<!-- auto-update 2023-12-02 14:07:15 -->

<!-- auto-update 2023-12-04 14:07:15 -->

<!-- auto-update 2023-12-06 14:07:15 -->

<!-- auto-update 2023-12-08 14:07:15 -->

<!-- auto-update 2023-12-10 14:07:15 -->

<!-- auto-update 2023-12-12 14:07:15 -->

<!-- auto-update 2023-12-14 14:07:15 -->

<!-- auto-update 2025-01-17 19:39:17 -->

<!-- auto-update 2025-01-19 19:39:17 -->

<!-- auto-update 2025-01-21 19:39:17 -->

<!-- auto-update 2025-01-23 19:39:17 -->

<!-- auto-update 2025-01-25 19:39:17 -->

<!-- auto-update 2025-01-27 19:39:17 -->

<!-- auto-update 2025-01-29 19:39:17 -->

<!-- auto-update 2025-01-31 19:39:17 -->

<!-- auto-update 2025-02-02 19:39:17 -->

<!-- auto-update 2025-02-04 19:39:17 -->

<!-- auto-update 2025-02-06 19:39:17 -->

<!-- auto-update 2025-02-08 19:39:17 -->

<!-- auto-update 2025-02-10 19:39:17 -->

<!-- auto-update 2025-02-12 19:39:17 -->

<!-- auto-update 2025-02-14 19:39:17 -->

<!-- auto-update 2025-02-16 19:39:17 -->

<!-- auto-update 2025-02-18 19:39:17 -->

<!-- auto-update 2025-02-20 19:39:17 -->

<!-- auto-update 2025-02-22 19:39:17 -->

<!-- auto-update 2025-02-24 19:39:17 -->

<!-- auto-update 2025-02-26 19:39:17 -->

<!-- auto-update 2025-02-28 19:39:17 -->

<!-- auto-update 2025-03-02 19:39:17 -->

<!-- auto-update 2025-03-04 19:39:17 -->

<!-- auto-update 2025-03-06 19:39:17 -->

<!-- auto-update 2025-03-08 19:39:17 -->

<!-- auto-update 2025-03-10 19:39:17 -->

<!-- auto-update 2025-03-12 19:39:17 -->

<!-- auto-update 2025-03-14 19:39:17 -->

<!-- auto-update 2025-03-16 19:39:17 -->

<!-- auto-update 2025-03-18 19:39:17 -->

<!-- auto-update 2025-03-20 19:39:17 -->

<!-- auto-update 2025-03-22 19:39:17 -->

<!-- auto-update 2025-03-24 19:39:17 -->

<!-- auto-update 2025-03-26 19:39:17 -->

<!-- auto-update 2025-03-28 19:39:17 -->

<!-- auto-update 2025-03-30 19:39:17 -->

<!-- auto-update 2025-04-01 19:39:17 -->

<!-- auto-update 2025-04-03 19:39:17 -->

<!-- auto-update 2025-04-05 19:39:17 -->

<!-- auto-update 2025-04-07 19:39:17 -->
