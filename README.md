# ULF-Wave-Analysis-Function
- ULF (Ultra-Low_Frequency) waves emerge from the constant struggle between two systems: The Sun's offensive solar wind, and the Earth's protective magnetic field.
- Plasma (a form of charged particles) from the Sun's solar wind also become trapped along the Earth's magnetic field lines, giving them a 'weight'.
- The Earth's magnetic field lines, given this 'weight', and the Sun's constant driving force, ripple like waves on a string.
- A major factor determining the frequency of these waves is the length of the field line, the length of the 'string' that these waves travel along.
- Given Earth's magnetic dipole, longer field lines occur further north, and consequently lower frequency 'ripples'
- These waves occur at a range of frequencies, but are particularly present in the 1.6mhz - 7mhz range, the ULF range. Here they also have a set of resonant frequencies of approximately 1.6mhz, 3.2mhz, 4.8mhz and 6.4mhz.
- Given these waves transfer energy from the Sun to our Earth, through the medium of our Earth's magnetosphere, they're key to understanding space weather events, interplanetary particle physics and planetary magnetic fields.

As part of my dissertation, I was given over 100 datasets of magnetometer readings over consecutive days across multiple locations.
I developed a function that would show the time series data alongside the same data after some signal processing and Fourier transforms.
Given that I was working with real world datasets, taken from a very chaotic system, most of the data isn't particularly useful. 
For this reason, I developed a function that shows the raw data alongside the analysed data, as the quality of the data can be determined largely through probing of the raw data alone. For example, there were significant dips and following volative turbulences in the raw time series dataset for almost every day, just after midday.
Furthermore, it was also important that any specified time range could be inputted, allowing for effective slicing and analysis of the dataset at time periods where the data was visibly useable after assessing the raw data alone. A key aim of the study was also investigating the attributes of waves at dawn, midday and dusk, so I needed to assess different time periods for this reason also.
Another key aim of the study was comparing data across different days and locations. To incorporate this, I had the function be able to take multiple datasets to compare ontop of eachother.

