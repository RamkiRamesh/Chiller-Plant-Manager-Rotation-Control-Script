# Chiller-Plant-Manager-Rotation-Control-Script
Flexible Chiller Plant Rotation
In Chiller Plant Manager, Rotation control of the Chillers and Pumps are very important topic,
I used to work with Chiller plant configuration with diffrent Brand and Model of Server/Controller.
But always having feel of not having felexible and suitable rotaninal block for my use cases.
Usually will create rotation seqenace by using basic blocks.
working with functional block is good to troubleshoot and the functinality is transparent.
but the problem with funtional block is difficult to handle Complex rotation order, time taking task to scale the number of units,occupy more memory space and visuval space.
So i started working on Java Script to make the Completly flexble and easy to scale the number of unit, handle Complex ratation order,enable and disbale run hour Based prioty.
Very first I implemented with chiller consiting of 7 chiller and 5 primary pumps.
Out of seven chillers fisrt 3 chiller(Group_01) always top priorty and  next 4 chiller alway least priority(Group_02),here grouping is easy because they in order,
but in pump it is little to difficult ,because group 01 is coinsist PUMP 1,3,5 and Group 02 consist of Pump 2,4 , 
i worked some complex coding and made it work as expected.
but in next projects the same sitution came with different Number of units and priority order, so every time i have invlpove in this complex codeing section.
so i decided to make simplfied method of implimenting this.
then found this way of implementing.
Will use multiple same base Roation block as per number group we have, and then i have additonal program for each Stage to replace the actual chiller number.
