---
already_read: false
link: https://erikbern.com/2024/04/07/predicting-solar-eclipses-with-python.html
read_priority: 1
relevance: 0
source: null
tags:
- Python
- Data_Visualization
type: Content
upload_date: '2024-04-10'
---

https://erikbern.com/2024/04/07/predicting-solar-eclipses-with-python.html
## Summary

Erik Bernhardsson's blog post details his approach to predicting solar eclipses using Python. He leverages the Astropy package to compute the positions of the sun and moon in the sky, calculating their angular separation to determine potential eclipses. The key steps include:

1. **Initial Calculation**: Using Astropy to find the angular separation between the sun and moon from a given Earth location and time.
2. **Optimization**: Employing black-box optimization (specifically, the Nelder-Mead method from SciPy) to find the latitude and longitude where the sun-moon separation is minimized, indicating a solar eclipse.
3. **Refinement**: Addressing issues like sign errors and spurious solutions by ensuring the sun and moon are above the horizon and using a grid search for initial optimization points.
4. **Scaling**: Using Modal to parallelize the computation across a decade (2020-2030) to find all eclipses, with a coarse search followed by a more granular one.
5. **Visualization**: Plotting the eclipse paths using Basemap, including local times and verifying the results against known eclipse data.

The post concludes with a list of eclipses found, noting the brute-force approach's productivity despite potential inefficiencies compared to more optimized methods. The code and additional details are available for further exploration.
## Links

- [Astropy](https://www.astropy.org/) : Astropy is a community-driven Python package for Astronomy. It contains core functionality and a uniform interface to resources for an expanding ecosystem of astronomical Python packages.
- [Modal](http://modal.com) : Modal is a platform for running Python code in the cloud. It provides a simple way to deploy and scale Python applications.
- [Timezonefinder](https://github.com/jannikmi/timezonefinder) : Timezonefinder is a fast, simple library for finding the timezone of any location on Earth.
- [Basemap](https://matplotlib.org/basemap/stable/) : Basemap is a matplotlib toolkit for plotting 2D data on maps. It provides a simple way to create maps and plot data on them.
- [Eclipse Finder](https://github.com/erikbern/eclipse-finder) : Eclipse Finder is a Python script that finds solar eclipses. It uses Astropy to compute the position of the sun and the moon in the sky and scipy.optimize to find the location of the eclipse.

## Topics

![](topics/Library/Astropy)

![](topics/Library/Scipy)

![](topics/Platform/Modal)

![](topics/Library/Basemap)

![](topics/Concept/Black%20box%20optimization)

![](topics/Concept/Celestial%20mechanics)