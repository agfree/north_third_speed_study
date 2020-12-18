# Speed on North Third Street


# Introduction
As a resident of North Third Street for several years, I have noticed an increase in traffic speeds corresponding with increased economic activity in the industrial area around the North Basin of the La Conner Marina, operated by the Port of Skagit County.  To make the case to the right audience, I started collecting data about traffic flow on the street.

# Methodology
Without access to precision radar sensors or other such equipment deployed by “real” traffic engineers, I decided to use computer-vision technology to measure traffic flow and direction.  The hardware for this project consisted of a high-resolution camera and a small computer suitable for outdoor use.  I placed the camera perpendicular to and a short distance away from the flow of traffic.  I drove my vehicle at 25 MPH by the camera system several times to serve as a calibration target.

![alt text](https://github.com/agfree/north_third_speed_study/blob/main/example.jpg?raw=true)

# Caveats
Due to computer-vision deficiencies, much like human vision, data was not collected when the camera could not “see” traffic flow, such as at night or in inclement weather.  Automobiles traveling at excessive speeds were not accurately recorded due to insufficient computing power, so all samples recorded above 50 MPH were discarded.  To eliminate bicycles, walkers, and cars that were slowing for a turn onto or off South Basin Street, I removed all samples below 18 MPH.

# Analysis

Time constraints and other problems related to 2020 took precedence over any in-depth statistical analysis of the dataset, so here are the basic facts.
* Over 23,500 samples were collected from Aug 8, 2019, to Aug 27, 2019. A sample consists of one car passing in front of the camera with a measurable speed derived.
* The average speed across all samples was 27.9 MPH, with a median of 25.81.  So far, so good.
* The 85th Percentile speed, which is important to traffic engineers and policymakers, was 37 MPH.  The 85th percentile speed indicates the speed that most motorists on the road consider safe and reasonable under ideal conditions. Traffic engineering manuals usually want this number to be less than 5-10 MPH above the posted speed limit.  We’re at 12 above.
* 2779 samples showed cars traveling between 40 and 50 MPH.  More than 3000 samples registering above 50 MPH were discarded for data quality purposes. Even if a small percentage were accurate, that shows many very high-speed vehicles on a 25 MPH street.

# Takeaways (where I get myself into trouble)

In many ways, speeding on North Third Street is entirely understandable and predictable.  It is a single path leading to a great deal of economic activity.  The industries served by this street are staffed by young, virile men who love fast cars and have short lunch breaks.  That being said, the speed problems have only increased since I collected this data more than one year ago.  What can be done?
* Enforcement (Sheriff) should be timed for shift changes at compaines around the North Basin.
* The Town could invest in a permanently installed radar-enabled speed limit sign for North Third or a portable unit (TC-400 from Radarsign) for use in all problem areas around town.
* Town government engagement directly with companies around the North Basin and/or the Port.
* More food trucks at the North Basin.

# Conclusion

I am not a traffic engineer, and my statistical analysis skills have faded somewhat due to disuse.  Thanks to a lot of reading and the project being in-line with many of my interests and hobbies, I learned a lot.  I hope I was able to provide a bit of clarity to the speeding problem on North Third Street.  Thanks for reading.
 

## References

1. Guan Xu, Federal Highway Administration, US Department of Transportation, Methods and Practices for Setting Speed Limits:An Informational Report
2. City of Delaware, Ohio, A Residential Guide to Neighborhood Speed Enforcement
3. Center for Transportation Research and Education, Iowa State University, Handbook of Simplified Practice for Traffic Studies

