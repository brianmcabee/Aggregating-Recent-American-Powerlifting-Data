# Aggregating Recent American Powerlifting Data
 ## A Python script to extract data from Unequipped American Powerlifters over the past five years

Notes: 
- The script to run the data extraction is located in the .ipynb file
- The input file is [openpowerlifting-2020-10-16.zip](https://github.com/brianmcabee/Aggregating-Recent-American-Powerlifting-Data/blob/main/openpowerlifting-2020-10-16.zip) and was retrieved from [OpenPowerlifting](https://www.openpowerlifting.org/)
- The output file can be downloaded [here](https://github.com/brianmcabee/Aggregating-Recent-American-Powerlifting-Data/blob/main/usa_sbd_data_2020-10-16.csv)
- To update this script to include more accurate information, simply read in a new OpenPowerlifting csv file in the first cell and then rename your new csv file in the last code cell.

This notebook was created to aggregate specific data provided by the OpenPowerlifting project into its own dataset. You may download an entire copy of the data here.

The python script written in this notebook retrieves relevant, accurate data from American Full-Power (Squat/Bench/Deadlift) competitors over the past few years. There have been no value modifications to the filtered data, as the sole purpose of this notebook is to only extract the relevant records that will be useful to myself, and hopefully others, for future analyses. The end result of this notebook is a new csv file with the relevant American powerlifting data.

For the sake of data accuracy, the new csv file will contain information from 2015 to present. Keep in my this option can be modified with the change of a parameter or two (as well as other filters to be discussed throughout the notebook). The reason for creating a new file is because the orginial csv file is pretty big, sitting at a little over 390MB at the time this notebook was created.
