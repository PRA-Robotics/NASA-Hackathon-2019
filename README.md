# NASA-Hackathon-2019

Intended to be a RePo for PRA Robotics hackathon space junk scavenger video game 
RL


Did a CURL query " curl --limit-rate 100K --cookie cookies.txt https://www.space-track.org/basicspacedata/query/class/tle_publish/PUBLISH_EPOCH/2019-10-17%2000:00:00--2019-10-18%2000:00:00/orderby/TLE_LINE1/format/tle --noproxy https://www.space-track.org/ > tle.txt

to create the "tie.txt". Then edited that txt file to create a CSV file "tle-CSV-added.txt". Then imported that into Excel and merged the line 1 and line 2 data and added column headings from the https://www.space-track.org/documentation#/tle help file. 

The column headings for line two indicate a Revolution count (which is very infrequently populated) and a checksum. 

I created the checksum for line 1 by Moving the Element Number by 10. I suppose I could do the same thing for the checksum for line 2 but didn't

In the tle2.xlsx file there's two tabs the first one has the merged lines (Line #1 and Line #2 on the same line with column headings) and the 2nd tab with the raw CSV data imported from tle-CSV-added.txt file
