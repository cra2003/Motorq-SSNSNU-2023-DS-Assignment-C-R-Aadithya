# Motorq-SSNSNU-2023-DS-Assignment-C-R-Aadithya

There were too many null values. Its hard to analyse with lesser amount of non-null values. 
The dataset was about vehicles and it's state at a given timestamp.

For the first question, I implemented linear search over the column to see if the ignition state was 'on' or 'off'.
I created a function that takes pnid as an input and returns the vehicle id that matches with it in the apping table. This way , I was able to get the ignition state from the triggers table as well

For the second question, I implemented the same steps that i did for the first question. But with a diffrent Event .

For the third question , I concantanated both the tables in the above questions with each row having a vehicle id , Event name and event 
timestamp.

For the 4th question , I implemented linear search to fill the battery levels for vehicles form telemetry table. I used the function to search for the vehicle id given the pnid as input that i created above. This way I got the batter levels from the triggers table.

Then for the null values, I found the closest timestamp and cheked if it was in range of 300 seconds to copy the same battery levels to it.

