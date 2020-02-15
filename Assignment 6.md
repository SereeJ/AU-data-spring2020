By first exporting the original CSV from The Washington post's GITHUB repository data-police-shootings, "fatal-police-shootings.csv," onto my computer, I was then able to import it into Google excel. Because the CSV was well filled out I didn’t have to organize much before starting my data set.

To further organize my data I created a series of pivot tables to derive my conclusions. To first create the pivot table, I clicked into ont of the filled in text boxes and hit [Select all Ctl+A] then went to Data > Pivot table. The specific steps I took from there are listed below.

--------

## For people like me, the safest place to be is Washington DC.


Africans are 2.5 more likely to be killed by policie than white men, but not in Washington D.C. The Washington Post has taken it upon themselves to do what few states fear to do, Track police fatalities. With tensions high, police are most likely to shoot only if the victum is also carrying a gun. 

Although The Washington post does a great job reporting their findings, one can only wonder how many of the “victims with guns” were alleged as many cops are without body cameras and therefore their actions cannot be visibly confirmed.  

Nevertheless, according to Nix’s  recently updated his analysis on police shootings using fatal and non-fatal shootings from the 47 largest metros from 2010 to 2016, we can find that Washington D.C rates the absolute lowest with a rating of 39.4%



1. Knowing that tensions are high in regards to police killings, particularly in the black community vs the white, I would like to examine just how disproportionate the numbers fall, within the last 5 years.

        Grand total of fatalities that were black within the last five years: 1117

        Grand total of fatalities that were White within the last five years:2132

Rows:

[ARMED] Order Descending - Sorted by 'COUNTA of armed'

Columns:

Values-

[ RACE ] Order Ascending - Sorted by Race

[ARMED] Summarized by COUNTA - Shown as Default

Filters-

[ARMED] Showing all items

2. Second, I would like to see and examine the top 5 items victims were armed with that caused the police to take defense. How many fatalities were a direct result of someone being armed with a gun?

        TOP FIVE ARMED:

        * gun	        2779

        * knife	730

        * unarmed	303

        * undetermined	200

        * toy weapon	173

Rows:

[ARMED] Order Descending - Sorted by 'COUNTA of armed'

Columns:

*Values-*

[ARMED] Summarized by COUNTA Shown as Default

*Filters-*

[ARMED] Showing all items

-------

**Over all number of fatalities:** 4736

    Calculated by Grand Total from pivot table editor

**Number of fatalities as a result of victim carring a gun:** 2779

[ Only 277 officers were reported to be wearing a body camera to confirm ]

    Calculated from Top Five
    
-------
    
  ## Original CSV // Document file
    
  https://github.com/washingtonpost/data-police-shootings/blob/master/fatal-police-shootings-data.csv
