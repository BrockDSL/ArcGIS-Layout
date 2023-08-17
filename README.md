  ![image of layout ribbon](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/efb732a9-53c3-40d1-b01b-09757c36b5f9)

# ArcGIS Pro Layout
This tutorial builds on the ArcGIS Visualization tuorial such that you are expected to have a map created using ArcGIS Pro. The following steps describe some basic pointers for creating a pleasing layout with cartographic elements such as legend, north arrow, scale bar, source statement and title.


----

## Setup Instructions
This tutorial assumes the user has completed the [ArcGIS Visualization](https://brockdsl.github.io/ArcGIS_Visualization/) tutorial.

This map package includes the final result of the ArcGIS Visualization tutorial. Download the [map package](https://github.com/BrockDSL/ArcGIS-Layout/blob/main/ArcGISLayout.mpkx) and double-click to run ArcGIS Pro.

----

## Creating a Layout
1. Click the **Insert** tab and select New Layout ![image of new layout button](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/53e18e94-3d3e-4345-92d2-3b01117532f7)
 
2. Select ANSI - Landscape 8.5" x 11"

The white box that appears is essentially the representation of a piece of letter size paper. It is a good practise to add **guides** so that there is a clean border around the outside of the map and all of its elements.

3. To be sure the rulers are showing, click the Layout ribbon at the top of the window and check the boxes for Rulers and Guides.
![image of show guides and rulers](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/0b5ed6c3-2581-4dd5-ac72-05572e9b8e05)

4. Above the white box you will see the ruler, right-click on the ruler and select **Add Guides...** Make sure to select GUIDES (plural) or you will end up with a single guide where you don't want it.

5. From the dialogue box, make the following selections:
- Orientation: BOTH
- Placement: Offset from edge
- Position: 0.5 in

   ![image showing add guides window](https://user-images.githubusercontent.com/45638590/229173445-5bb1b068-393d-4c35-990e-0492bd71fd13.png)

6. Click OK to add the guides. When you add any element to the layout, DO NOT ALLOW ANY PART TO CROSS OVER THE GUIDES.

The **Insert** tab at the top is where you will find a variety of elements to add to the layout.

7. From the **Insert** tab at the top, select **Map Frame** ![image of insert > map frame](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/0bd90166-1155-4781-8e3d-968ab411cdf6). Choose the map frame to add. In this case, ![image of map frame to insert](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/d52a5667-ba33-427e-8d22-cbf35eeef808).

8. Draw a box on the layout page to represent the map element. The box is populated with the map frame and should look something like this:

![image](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/9759d785-573e-478a-b93a-3e694e9b7b68)


9. Use the handles (little white boxes on the edge and corners of the map frame) to resize and click/drag to re-position the map element. Notice the space above and below for text such as title and source statements. There is also room to the right of the map for a legend, north arrow and scale bar.

10. With the Insert ribbon active, explore the options from the **Map Surrounds** group. We will add a few of these elements next.

![image](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/8534626b-23ee-4937-bd00-e92ccb9d06fe)


11. Click the North Arrow option and select a style of your choosing then click anywhere on the layout to add the north arrow. With the north arrow element selected, click/drag to position it on the layout.

12. Likewise, click the scalebar options and choose a **metric** scalebar then click on the layout to place the element. Double click the scalebar to see more options.    
    ![image of scalebar settings](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/181522ff-8f0a-4e84-8ba5-0445a07f3241)    

    ![image showing north arrow and scalebar added](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/85c2e58a-0380-45a9-847a-e45dd787630d)

## The Legend

1. From the Insert ribbon, click the legend option and select "Legend 1" then draw a box on the layout.  

2. If you see 3 red dots inside square brackets, this means there is more content to be seen. Widen the legend box until the red dots disappear.

3. Double-click the legend element to see options.

    ![image of legend element options](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/8359615f-bb3e-4020-ab43-de95c4b7491a)

4. From *Legend Items* click **Show Properties** ![image legend items show properties](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/d39508f8-179e-4b90-86a3-53627a58c540)

From **Feature Display Options** check the boxes for *Only show features visible in the map extent* and *Show feature counts*. 

Experiment with other options and shift layout elements as desired. Here is what your map could look like:    

![image of sample map](https://github.com/BrockDSL/ArcGIS-Layout/assets/45638590/bfa225c2-957c-4296-8002-25e7290934ca)





----

## Next Steps (Optional)
This is where you can add any additional resources, follow up tutorial, or workshop reccomendations that users might use to continue learning about the tool described in the tutorial.  The more the better!

----

**End notes**
This is where you mention the DSL, MDGL, or Research Lifecycle department and put in contact information.  An example of what this might look like is:

**This tutorial is supported by the Brock University Research Lifecycle Department.  If you have any questions or concerns regarding this tutorial, don't hesitate to contact [DSL@Brocku.ca](mailto:DSL@Brocku.ca)**
