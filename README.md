![This is an Image](/img.png)

# Customer Service Requests Analysis
**Project 1** 

**_DESCRIPTION_**

## Background of Problem Statement :

NYC 311's mission is to provide the public with quick and easy access to all New York City government services and information while offering the best customer service. Each day, NYC311 receives thousands of requests related to several hundred types of non-emergency services, including noise complaints, plumbing issues, and illegally parked cars. These requests are received by NYC311 and forwarded to the relevant agencies such as the police, buildings, or transportation. The agency responds to the request, addresses it, and then closes it.

## Problem Objective :

Perform a service request data analysis of New York City 311 calls. You will focus on the data wrangling techniques to understand the pattern in the data and also visualize the major complaint types.
Domain: Customer Service

## Analysis Tasks to be performed: 
#### _(Perform a service request data analysis of New York City 311 calls)_ 

   1. Import a 311 NYC service request.
   2. Read or convert the columns "**Created Date**" and "**Closed Date**" to datetime datatype 
      and create a new column "**Request_Closing_Time**" as the time elapsed between request creation 
      and request closing. (Hint: Explore the package/module datetime)
   3. Provide major insights/patterns that you can offer in a visual format (graphs or tables)
      at least 4 major conclusions that you can come up with after generic data mining.
   4. Order the complaint types based on the average "**Request_Closing_Time**", grouping them 
      for different locations.
   5. Perform a statistical test for the following:
      Please note: For the below statements you need to state the Null and Alternate and then 
      provide a statistical test to accept or reject the Null Hypothesis along with 
      the corresponding "**p-value**".

      - Whether the average response time across complaint types is similar or not (overall)
      - Are the type of complaint or service requested and location related?

## Dataset Description :

Field	Description
- Unique Key	(Plain text) - Unique identifier for the complaints
- Created Date	(Date and Time) - The date and time on which the complaint is raised
- Closed Date	(Date and Time)  - The date and time on which the complaint is closed
- Agency	(Plain text) - Agency code
- Agency Name	(Plain text) - Name of the agency
- Complaint Type	(Plain text) - Type of the complaint
- Descriptor	(Plain text) - Complaint type label (Heating - Heat, Traffic Signal Condition - Controller)
- Location Type	(Plain text) - Type of the location (Residential, Restaurant, Bakery, etc)
- Incident Zip	(Plain text) - Zip code for the location
- Incident Address	(Plain text) - Address of the location
- Street Name	(Plain text) - Name of the street
- Cross Street 1	(Plain text) - Detail of cross street
- Cross Street 2	(Plain text) - Detail of another cross street
- Intersection Street 1	(Plain text) - Detail of intersection street if any
- Intersection Street 2	(Plain text) - Detail of another intersection street if any
- Address Type	(Plain text) - Categorical (Address or Intersection)
- City	(Plain text) - City for the location
- Landmark	(Plain text) - Empty field
- Facility Type	(Plain text) - N/A
- Status	(Plain text) - Categorical (Closed or Pending)
- Due Date	(Date and Time) - Date and time for the pending complaints
- Resolution Action Updated Date	(Date and Time) - Date and time when the resolution was provided
- Community Board	(Plain text) - Categorical field (specifies the community board with its code)
- Borough	(Plain text) - Categorical field (specifies the community board)
- X Coordinate	(State Plane) (Number)<
- Y Coordinate	(State Plane) (Number)
- Park Facility Name	(Plain text) - Unspecified
- Park Borough	(Plain text) - Categorical (Unspecified, Queens, Brooklyn etc)
- School Name	(Plain text) - Unspecified
- School Number	(Plain text)  - Unspecified
- School Region	(Plain text)  - Unspecified
- School Code	(Plain text)  - Unspecified
- School Phone Number	(Plain text)  - Unspecified
- School Address	(Plain text)  - Unspecified
- School City	(Plain text)  - Unspecified
- School State	(Plain text)  - Unspecified
- School Zip	(Plain text)  - Unspecified
- School Not Found	(Plain text)  - Empty Field
- School or Citywide Complaint	(Plain text)  - Empty Field
- Vehicle Type	(Plain text)  - Empty Field
- Taxi Company Borough	(Plain text)  - Empty Field
- Taxi Pick Up Location	(Plain text)  - Empty Field
- Bridge Highway Name	(Plain text)  - Empty Field
- Bridge Highway Direction	(Plain text)  - Empty Field
- Road Ramp	(Plain text)  - Empty Field
- Bridge Highway Segment	(Plain text)  - Empty Field
- Garage Lot Name	(Plain text)  - Empty Field
- Ferry Direction	(Plain text)  - Empty Field
- Ferry Terminal Name	(Plain text)  - Empty Field
- Latitude	(Number) - Latitude of the location
- Longitude	(Number) - Longitude of the location
- Location	(Location) - Coordinates (Latitude, Longitude)