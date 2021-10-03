# mappingtool-01 caribiou(point to line)

## introduction

caribou(point to line) is a grasshopper file for finding the line of the nearest point.

It works by the points on the determined map are connected to form a net. So as to form a network cable within the set distance.

## For Alpha Section

## examples
select the city
Barcelona 

one type point-line(factory) ![ViewCapture20210821_180846](https://user-images.githubusercontent.com/89188002/130344402-dcac41ad-3cdb-45fd-bf0d-4db48e1d7762.jpg)
the connection between those two types(office/cafe)![ViewCapture20210822_142859](https://user-images.githubusercontent.com/89188002/130345011-95219032-f0f0-410e-9ca5-254e82c14032.jpg)

## use

step1  Position the map to the midpoint, and then assign the required locations to different terrains.

step2  Show location or terrain connection

step3  Adjust the distance and contact points

step3  Connect the required points

step4  Determine the connection between the core location and the surrounding area

## For Beta Section
#  mappingtool-02 place of public entertainment around the parks （Grid-Field Analyses）

## introduction

This plugin，Grid-Field Analyses， is to help people better understand a strange city.

Through the visualization effect of the grid, to interpret which places in a city are crowded with people and which places are free.


## examples 01 Stage1
Barcelona 
Restaurants, entertainment and other places are located in the central area and near the downtown business district, so the demand for parking berths is relatively tight.
During the peak period of holidays, the demand for parking is larger than usual, and the vehicle congestion is serious. The problem of parking difficulty is obviously aggravated.
![01](https://user-images.githubusercontent.com/89188002/132467069-aba33399-dc8d-414f-b5b9-a1a550915b1d.jpg)


Point approach and avoidance
around the College/Unviercity ![微信图片_20210908150902](https://user-images.githubusercontent.com/89188002/132464712-b3f65146-12b5-407b-95ac-9d727251c3bc.png)
![0f59c7aa0bbf1a3ae7bf0174307bd0f](https://user-images.githubusercontent.com/89188002/132464816-4153d15d-5353-42a1-8aa4-02eefc9b7a25.png)
around the bar![37337cb010fab8d2ac37cce2df8f093](https://user-images.githubusercontent.com/89188002/132464922-04e1eee0-37df-4459-bf0c-e53e18a50031.png)
around the coffee ![24280d13bdbc6015587957dd99ef596](https://user-images.githubusercontent.com/89188002/132464980-b507fb21-1aa9-4402-9c93-a93698aa9915.png)

Areas Approach and avoidance
around the park![3f592765c5e5737d4ccd84a9939b94b](https://user-images.githubusercontent.com/89188002/132465314-ee1d616e-f8dc-4338-8169-9941ed71bdb1.png)

Composite image
[02.pdf](https://github.com/i9yogurt/granary/files/7126772/02.pdf)

 
## use
step1  Decide on the different layers to choose, such as cafes or schools or parks. Call up the point or area of the selected area.

step2  Select the desired points to connect in the grid for testing and adjustment.

step3  Adjust the data and contact points

step3  The style of the selected area or point will be displayed in the plug-in, and the shape can be adjusted.

step4  Determine the connection between the core location and the surrounding area

## examples 01 Stage2

Barcelona
General entertainment and catering establishments, such as cafes, bars and restaurants, mainly provide places for urban residents' daily leisure, food and other activities. The parking demand of this kind of places is relatively large, and the parking volume is relatively large during a certain period of time. They are generally located in the city center or densely populated areas, and relatively few parking resources on the ground. Especially during holidays, the contradiction between the increasing demand for parking and the lack of parking facilities is increasing, which will also adversely affect the surrounding dynamic traffic. The parking turnover rate in this type of area is relatively large, and the number of parking is relatively large, which has become a more prominent area of urban parking difficulties. For catering and entertainment land, whether it can provide comfortable and convenient services is the basic requirement of its operation. Good services include factors such as the convenience of transportation and the convenience of parking. Therefore, the grid plug-in is used to simulate road land and route planning for people's routes, thereby solving the interface relationship between traffic landscape and street landscape.
![image](https://user-images.githubusercontent.com/89188002/135760991-fbd7e6fd-033e-4340-80d7-0b103b8bf770.png)

## issues and goals of future countermeasures
·Is it necessary to modify the surrounding green space, increase mechanical parking spaces or increase on-street parking on secondary roads and branch roads to reduce the impact on the dynamic traffic around the main road?
·Is it possible to use the idle parking lots of the surrounding businesses for parking, so as to meet the parking demand and rational use of parking resources?
·In order to better avoid the impact on the internal dining and entertainment, the parking lot can be set up outside the dining and entertainment areas, so as to reduce the traffic impact on the central area?

## examples 01 Stage3

#  mappingtool-03 Data analysis of parking demand （Chart Analyses）
## introduction

This plug-in has a chart template, which can be tested multiple times by changing the value and chart type.

## examples
By observing the proportion of the number, consider how to increase the number of parks.
![9418b2610580e8f8908f770da992a3b](https://user-images.githubusercontent.com/89188002/135762613-4bd5d7f6-301e-45b0-9ac2-eba1a754b198.png)

According to the proportion of parks used by different places, the land in that area can be divided.
![4d583d9e0accd0da3369e1e078151ae](https://user-images.githubusercontent.com/89188002/135762620-6654db6b-cba0-4246-99fe-258fd57034d1.png)

For different visitors, the parks of the venue should be allocated reasonably
![42448ff688d4f7d08a57553cefed5a4](https://user-images.githubusercontent.com/89188002/135762624-0f86a20b-d232-4fdc-a296-92ea939ab9b0.png)

## use

This is easy to use, only need to pay attention to three points
Step1 Adjust the number
![image](https://user-images.githubusercontent.com/89188002/135762865-58ca511c-67db-447a-b70d-ce9756cacb5d.png)
![a7032909eb4e3906e72eac609c59140](https://user-images.githubusercontent.com/89188002/135762847-d845b6d7-d31a-4f86-8c11-4b90e97e2aa3.png)
Step2  Adjust chart type
![369c68fdcbe562798ce8eb83db71358](https://user-images.githubusercontent.com/89188002/135762898-a5cbc423-c828-4682-967f-da61516b0148.png)
Step3  Adjust color
![fe79cf09ed3ba66be8ea50cd3a1710a](https://user-images.githubusercontent.com/89188002/135762940-2bd9ba33-2cc3-4704-9856-f1cb6d42f3e3.png)



