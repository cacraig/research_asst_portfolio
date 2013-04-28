<p>The State Climate Office of North Carolina employed me to advance thier quality control capabilities with respect to 
climate variables. The NC SCO operates a mesonet (Distribution of weather stations) across the spatial extent of NC. These stations
obtain daily/hourly/minutely data of various parameters including (but not limited to) Solar Radiation, Precipitation, Wind speed and direction
(at various levels), and Soil temperature.</p>

<p>Quality Control is operated every hour, and is performed by Perl scripts (running as a Cron-jobs). About 70% of my work at the NC SCO was dedicated to improving thier
QC ability, as climate data integrity is of utmost importance to a multitude of fields/sectors (Agriculture, Hydrology, Meteorology, etc. ). </p>

<p> QC_Rain.pm is entirely authored by me. This script runs on hourly ECONet Gauge and Impact Sensor data. 
It is in an intersensor comparison that also pulls Multisensor Precipitation Estimates (MPE) as a means of a third party comparison. 
It returns flagged observations. </p>
<p>
QC.pl, is the 'main' script of the Automated NC SCO Quality Control program. 
It is authored by a variety of people including Micheal Diaz, Aarron Simms, Sean Heuser, and I. 
While only some the code is authored by me, I included this in my portfolio in order to give a sense of how this program works.

I cannot include the entire program, but I did include the parts that I authored or co-authored.
</p>
