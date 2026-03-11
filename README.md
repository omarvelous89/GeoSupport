# GeoSupport
Cleaning and retrieving geographic data. We start with an input file comprised of user created profiles. We proceed to clean & process the data to prepare it for calls to GeoSupport, a repository of NYC geographical data, & future re-import. 

After cleaning and processing we then proceed to the main goal, which is appending each row with the data we require from GeoSupport. In this case we are retrieving the NYC City Council, NYS Assembly, NYS Senate and US Congressional Districts. This information is then used for planning, policy and advocacy efforts at the leadership level.

Also included in the code is some basic error handling when appending the data in order to reduce manual work.
