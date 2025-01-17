# Transients and Other Time Series Science

* Focusing on the detection and analysis of any object that shows flux variation.
    - For example: variable stars, TDE, and eclipsing binaries.
    - **Exoplanet** and **supernova** are also trasients, but they have much broader impact therefore they have their own topics.

## Transient Notification

- [pycgn - Python package for processing Gamma-ray Coordinates Network (GCN) notices and circulars ](https://github.com/lpsinger/pygcn)
    * Anonymous VOEvent client for receiving GCN/TAN notices in XML format

## Differential Photometry

- [lemon - Differential photometry for humans (and astronomers)](https://github.com/vterron/lemon)
    * By Víctor Terrón. `LEMON` is a differential-photometry pipeline, written in Python, that determines the changes in the brightness of astronomical objects over time and compiles their measurements into light curves.
- [hotpants - High Order Transform of Psf ANd Template Subtraction code](https://github.com/acbecker/hotpants)
    * By Andy Becker.
- [astrobase - Python modules for light curve work and variable star astronomy](https://github.com/waqasbhatti/astrobase)
    * By [Waqas Bhatti](https://wbhatti.org/). It includes implementations of several period-finding algorithms, batch work drivers for working on large collections of light curves, and a small web-app useful for reviewing and classifying light curves by stellar variability type.

## Trasient Identification and Classification

- [astrorapid - Real-time Automated Photometric IDentification (RAPID) of astronomical transients using deep learning](https://github.com/daniel-muthukrishna/astrorapid)
    * By [Daniel Muthukrishna](http://www.danielmuthukrishna.com/). `RAPID` (Real-time Automated Photometric IDentification) can classify multiband photometric light curves into several different transient classes. It uses a deep recurrent neural network to produce time-varying classifications.
- [astrodash - Deep learning for the automated spectral classification of supernovae](https://github.com/daniel-muthukrishna/astrodash)
    * By [Daniel Muthukrishna](http://www.danielmuthukrishna.com/). Software to classify the type, age, redshift and host for any supernova spectra. Two platforms exists: a python library that enables a user to classify several spectra (can classify thousands of spectra in seconds), and also a graphical interface that enables a user to view and classify a spectrum. 
- [UPSILoN - Automated Classification of Periodic Variable Stars Using Machine Learning](https://github.com/dwkim78/upsilon)
    * UPSILoN (AUtomated Classification of Periodic Variable Stars using MachIne LearNing)

## Lightcurve and Exoplanet

- [lightkurve - A friendly package for Kepler & TESS time series analysis in Python](https://github.com/KeplerGO/lightkurve)
    * `Lightkurve` is a community-developed, open-source Python package which offers a beautiful and user-friendly way to analyze astronomical flux time series data, in particular the pixels and lightcurves obtained by NASA's Kepler and TESS exoplanet missions.

- [eleanor - light curves from TESS](https://github.com/afeinstein20/eleanor)
    * `eleanor` is a python package to extract target pixel files from TESS Full Frame Images and produce systematics-corrected light curves for any star observed by the TESS mission.

- [starry - Analytic occultation light curves for astronomy]()
    * By [Rodrigo Luger](https://rodluger.github.io/). Based on [a very nice paper](https://docs.google.com/viewer?url=https://github.com/rodluger/starry/raw/master-pdf/tex/starry.pdf)

- [everest - EPIC Variability Extraction and Removal for Exoplanet Science Targets](https://github.com/rodluger/everest)
    * A pipeline for de-trending K2 light curves with pixel level decorrelation and Gaussian processes.]

- [wotan - Automagically remove trends from time-series data](https://github.com/hippke/wotan)
    * By [Michael Hippke](http://www.jaekle.info/). Offers free and open source algorithms to automagically remove trends from time-series data.
