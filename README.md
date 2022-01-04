# gpx-extraction
A simple python program to extract the height climb from a gpx file under the assumption no stops were made.
The development steps of this are:
1. Work out the time and distance under the same assumptions
2. To process large numbers of gpx files gathered from Strava and compare the height climb calculated directly from the file vs the climb strava gives so see if there is any correlations.
3. Work out how Strava gpx data deals with stopping of the watch when recording an activity. Then repeat everything taking this into account.

