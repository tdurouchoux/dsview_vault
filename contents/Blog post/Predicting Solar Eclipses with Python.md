---
already_read: false
link: https://erikbern.com/2024/04/07/predicting-solar-eclipses-with-python.html
read_priority: 1
source: null
tags:
- Python
type: Content
upload_date: '2024-04-10'
---

https://erikbern.com/2024/04/07/predicting-solar-eclipses-with-python.html
## Summary

The article discusses how to predict solar eclipses using Python, specifically leveraging the Astropy library for astronomical calculations. The author outlines the process of computing the angular separation between the sun and the moon from a given location on Earth, which indicates a solar eclipse when the separation is near zero.

Key technical points include:

1. **Angular Separation Calculation**: A function is created to compute the angular separation between the sun and moon using latitude, longitude, and a timestamp.

2. **Black-Box Optimization**: To find the coordinates of a total eclipse, the author employs black-box optimization with `scipy.optimize.minimize`, minimizing the distance between the sun and moon for a given timestamp.

3. **Eclipse Location Function**: The function `find_eclipse_location` is designed to return the coordinates of a total eclipse or `None` if no eclipse occurs.

4. **Finding Multiple Eclipses**: The author outlines a method to find all eclipses from 2020 to 2030 by performing a coarse search over timestamps and then refining the search for identified eclipses. This process is parallelized using Modal, a cloud computing platform.

5. **Plotting Eclipses**: The article describes how to visualize the eclipse paths using the Basemap library in Matplotlib, providing a simple yet effective way to display the results.

The final output includes a list of solar eclipses occurring between 2020 and 2030, confirming the accuracy of the predictions against existing data. The approach is noted for its simplicity and effectiveness, despite being computationally intensive.
## Links

1. [Astropy](https://www.astropy.org/) - A Python package for astronomy that provides tools for celestial mechanics and coordinate transformations.
2. [scipy.optimize](https://docs.scipy.org/doc/scipy/reference/optimize.html) - Documentation for the optimization routines in SciPy, useful for minimizing functions.
3. [Basemap](https://matplotlib.org/basemap/stable/) - A toolkit for plotting 2D data on maps in Python, useful for visualizing the paths of solar eclipses.
4. [timezonefinder](https://github.com/jannikmi/timezonefinder) - A Python library for finding the timezone of a given latitude and longitude, useful for local time calculations during eclipses.
5. [Nelder-Mead](https://en.wikipedia.org/wiki/Nelder%E2%80%93Mead_method) - Wikipedia page explaining the Nelder-Mead optimization method, which is used in the context of black-box optimization in the article.
## Topics

- [[topics/Library/Astropy]]
- [[topics/Library/SciPy]]
- [[topics/Platform/Modal]]
- [[topics/Library/Basemap]]
- [[topics/Concept/Black-box optimization]]