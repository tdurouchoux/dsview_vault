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

1. **Initial Calculation**: Using Astropy, he computes the angular separation between the sun and moon from a given Earth location and timestamp.
2. **Optimization**: He employs black-box optimization with SciPy to find the latitude and longitude that minimize this separation, indicating a solar eclipse.
3. **Refinement**: He addresses issues like sign errors and spurious coordinates by ensuring the sun and moon are above the horizon and using a grid search for initial optimization points.
4. **Finding Eclipses**: He searches for eclipses over a decade (2020-2030) by coarse-grained timestamp probing, followed by granular searches and parallel processing using Modal for scalability.
5. **Plotting**: He uses Basemap to plot the eclipse paths, adding local times with timezonefinder.

The post concludes with a list of eclipses found, matching online sources, and notes on the brute-force approach's productivity benefits despite its computational cost. The code and further details are available in the provided links.
## Links

- [Eclipse Finder GitHub Repository](https://github.com/erikbern/eclipse-finder) : The GitHub repository containing the code for predicting solar eclipses using Python.
- [Astropy Documentation](https://www.astropy.org/) : The official documentation for Astropy, a key library used in the article for celestial coordinate calculations.
- [Modal Documentation](https://modal.com) : Modal is a platform used for running Python code in the cloud, mentioned in the article for parallelizing computations.
- [Scipy Optimize Documentation](https://docs.scipy.org/doc/scipy/reference/optimize.html) : Documentation for Scipy's optimization routines, used in the article for minimizing the distance between the sun and the moon.
- [Basemap Documentation](https://matplotlib.org/basemap/stable/) : Documentation for Basemap, a library used for plotting maps, including eclipse paths.

## Topics

![[topics/Library/Basemap)]]

![[topics/Library/SciPy)]]

![[topics/Library/Astropy)]]

![[topics/Platform/Modal)]]