The Data used for the analysis and prediction contains a lots of rows and columns regarding the collisions statistics.
The dataset is rich in attribute and contains a lots of information needed for analysis.
It includes severity, fata rates, timezones, no of accidents, types of injuries and many more attributes.

## Data Set Summary

The dataset contains all collisions provided by SPD and recorded by Traffic Records. This includes all types of collisions. Collisions will display at the intersection or mid-block of a segment. <br>
<code>Timeframe</code>: 2004 to Present.

## The various attributes of the dataset are:

    - OBJECTID: unique identifier
    - SHAPE: Geometry field
    - INCKEY: Long unique key for the incident
    - ADDRTYPE: Collision address type:
        • Alley
        • Block
        • Intersection
    - INTKEY: Key that corresponds to the intersection associated with a collision.
    - LOCATION: Location where the collision occurred
    - SEVERITYCODE: A code that corresponds to the severity of the collision:
        • 3—fatality
        • 2b—serious injury
        • 2—injury
        • 1—prop damage
        • 0—unknown
    - WEATHER: weather conditions during the time of the collision.
    - ROADCOND: The condition of the road during the collision.
    - LIGHTCOND: The light conditions during the collision.
    - PEDROWNOTGRNT: Whether or not the pedestrian right of way was not granted. (Y/N)
    - SPEEDING: Whether or not speeding was a factor in the collision. (Y/N)
    - UNDERINFL: Whether or not a driver involved was under the influence of drugs or alcohol.
    - INATTENTIONIND: Whether or not collision was due to inattention. (Y/N)
    - JUNCTIONTYPE: Category of junction at which collision took place
    
    - and many more.
<br>

## Some of the essential attribute for the training and building the model are as follows:

    - LOCATION
    - WEATHER
    - ROADCOND
    - LIGHTCOND
    - PEDROWNOTGRNT
    - SPEEDING
    - UNDERINFL
    - INATTENTIONIND
    - JUNCTIONTYPE

<br>

## State Collision Code

<h4>Code Descriptions</h2>

<table style="width:100%">
  <tr>
    <td><i><b>Code</b></i></td>
    <td><i><b>Description</b></i></td> 
  </tr>
  <tr>
    <td>0</td>
    <td>Vehicle Going Straight Hits Pedestrian</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Vehicle Turning Right Hits Pedestrian</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Vehicle Turning Left Hits Pedestrian</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Vehicle Backing Hits Pedestrian</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Vehicle Hits Pedestrian - All Other Actions</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Vehicle Hits Pedestrian - Actions Not Stated</td>
  </tr>
  <tr>
    <td>10</td>
    <td>Entering At Angle</td>
  </tr>
  <tr>
    <td>11</td>
    <td>From Same Direction -Both Going Straight-Both
Moving- Sideswipe</td>
  </tr>
  <tr>
    <td>12</td>
    <td>From Same Direction -Both Going Straight-One
Stopped- Sideswipe </td>
  </tr>
  <tr>
    <td>13</td>
    <td>From Same Direction - Both Going Straight - Both
Moving - Rear End </td>
  </tr>
</table>