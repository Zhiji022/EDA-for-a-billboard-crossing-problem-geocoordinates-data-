
## Background

Gps coordinates (simulated) are collected from mobil devices along a road in a residential area. The road is split into three sections, labelled by the column poi_sequence, which is a sequence number of the road section (the sequence numbers are -1,0, or 1). There are two billboards in sequence 0, one facing east and the other facing west. Devices who are seen in sequence -1, then 0 and then 1 are travelling east.  Devices with the reverse order are therefore travelling west.

## Challenges

- Determine the total number of trips and total number of unique devices
- Determine the distribution of average number of trips per device for each board
- For each board make an hour of day distribution that clearly shows any peak or low traffic times.
- Estimate the velocity of devices that pass each billboard.
- Determine the uncertainty

## Some assumptions

- All devices crossing sequence 0 saw the billboard.
- The uncertainty of gps coordinates is normally distributed with 1 standard deviation of 50 meters.
- The uncertainty is only in latitude.
