# Speed on North Third Street


# Introduction
As a resident of North Third Street for several years, I have noticed an increase in traffic speeds corresponding with increased economic activity in the industrial area around the North Basin of the La Conner Marina.  To make the case to the right audience, I started collecting data about traffic flow on the street.

# Methodology
Without access to precision radar sensors or other such equipment deployed by “real” traffic engineers, I decided to use computer-vision technology to measure traffic flow and direction.  The hardware for this project consisted of a high-resolution camera and a small computer suitable for outdoor use.  I placed the camera perpendicular to and a short distance away from the flow of traffic.  I drove my vehicle at 25 MPH by the camera system several times to serve as a calibration target.

![alt text](https://github.com/agfree/north_third_speed_study/blob/main/example.jpg?raw=true)

# Caveats
Due to computer-vision deficiencies, much like human vision, data was not collected when the camera was unable to “see” traffic flow, such as at night or in inclement weather.  Automobiles traveling at excessive speeds were not accurately recorded due to insufficient computing power, so all samples recorded above 50 MPH were discarded.  To eliminate bicycles, walkers, and cars that were slowing for a turn onto or off South Basin Street, I removed all samples below 18 MPH.
