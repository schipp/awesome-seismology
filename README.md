# Awesome Seismology

> A curated list of awesome tools and resources for seismologists.

- [Awesome Seismology](#awesome-seismology)
  - [Array seismology](#array-seismology)
  - [Earthquake bulletins/catalogues](#earthquake-bulletinscatalogues)
  - [Earthquake analysis](#earthquake-analysis)
  - [Educational resources](#educational-resources)
  - [Distributed acoustic sensing](#distributed-acoustic-sensing)
  - [Geodetics](#geodetics)
  - [Inversion \& Inference](#inversion--inference)
  - [Marine Seismology](#marine-seismology)
  - [Machine learning](#machine-learning)
  - [Seismic data access](#seismic-data-access)
  - [Seismic data handling](#seismic-data-handling)
  - [Seismic interferometry \& ambient noise](#seismic-interferometry--ambient-noise)
  - [Source localisation](#source-localisation)
  - [Structure imaging](#structure-imaging)
  - [Synthetic seismograms](#synthetic-seismograms)
  - [Synthetic travel times, ray parameters and ray paths](#synthetic-travel-times-ray-parameters-and-ray-paths)
  - [Visualisation](#visualisation)

## Array seismology

- [acoular](https://www.acoular.org) - Acoustic testing and source mapping software ![python](assets/python.png)
- [B3AM](https://github.com/katrinloer/B3AM) / [B3Ampy](https://github.com/cl-finger/B3Ampy) - toolbox for easy and fast beamforming analysis of three-component array data ![matlab](assets/matlab.png)/![python](assets/python.png)
- [beampower](https://github.com/ebeauce/beampower) - Beamforming (or backprojection) of seismic signal for event detection and location ![python](assets/python.png)
- [covseisnet](https://github.com/covseisnet/covseisnet) - array covariance matrix analysis ![python](assets/python.png)
- [fast_beamforming](https://github.com/schipp/fast_beamforming) - Fast and efficient beamforming in Python ![python](assets/python.png)

## Earthquake bulletins/catalogues

- [BGR](https://www.szgrf.bgr.de) - Bulletin of the Federal Institute for Geosciences and Natural Resources, Germany
- [EMSC](https://emsc-csem.org) - Bulletin of the Euro-Mediterranean Seismological Centre
- [GEOFON](https://geofon.gfz-potsdam.de) - Bulletin of the GeoForschungsZentrum Potsdam, Germany
- [Global CMT](https://www.globalcmt.org) - Bulletin of the Global Centroid-Moment-Tensor (CMT) Project
- [ISC](https://www.isc.ac.uk/iscbulletin/) - Bulletin of the International Seismological Centre, UK
- [IGN](https://www.ign.es/web/en/ign/portal/sis-catalogo-terremotos) - Bulletin of the Instituto Geografico Nacional, Spain
- [SED](http://www.seismo.ethz.ch/en/home/) - Bulletin of the Swiss Seismological Service, Switzerland
- [USGS](https://earthquake.usgs.gov/earthquakes/map/) - Bulletin of the US Geological Survey, USA

## Earthquake analysis

- [Grond (pyrocko)](https://pyrocko.org) - Probabilistic source optimization ![python](assets/python.png)
- [BEAT (pyrocko)](https://pyrocko.org) - Bayesian Earthquake Analysis Tool ![python](assets/python.png)
- [BPMF](https://github.com/ebeauce/Seismic_BPMF) - Earthquake detection and location with GPU-accelerated processing ![python](assets/python.png)
- [focmec](https://seiscode.iris.washington.edu/projects/focmec) - Package for determining and displaying earthquake focal mechanisms
- [PhaseNet](https://github.com/AI4EPS/PhaseNet) - A Deep-Neural-Network-Based Seismic Arrival Time Picking Method ![python](assets/python.png)
- [SEISAN](https://seisan.info) - Earthquake analysis software ![fortran](assets/fortran.png)
- [SeisSol](https://seissol.org) - A software package for simulating wave propagation and dynamic rupture ![cpp](assets/cpp.png)

## Educational resources

- [seismo-live](https://seismo-live.github.io) - Live Jupyter Notebooks for Seismology ![python](assets/python.png)

## Distributed acoustic sensing

- [awesome-das](https://github.com/DAS-RCN/awesome-das) - A curated list of awesome resources for distributed acoustic sensing (DAS).
- [DASCore](https://dascore.netlify.app) - A python library for distributed fiber optic sensing ![python](assets/python.png)

## Geodetics

- [geokernels](https://github.com/sigmaterra/geokernels) - Fast geospatial distance and geodesic kernel computation ![python](assets/python.png)

## Inversion & Inference

- [BayesBay](https://github.com/fmagrini/bayes-bay) - generalised trans-dimensional and hierarchical Bayesian inference ![python](assets/python.png)
- [pyGIMLi](https://www.pygimli.org) - Multi-method modelling and inversion in geophysics ![python](assets/python.png)

## Marine Seismology

- [OCloC (OBS Clock Correction)](https://ocloc.readthedocs.io/en/latest/index.html) - detect and correct timing errors when using passive seismic records ![python](assets/python.png)

## Machine learning

- [SeisBench](https://github.com/seisbench/seisbench) - Python toolbox for machine learning in seismology ![python](assets/python.png)
- [PhaseNet](https://github.com/AI4EPS/PhaseNet) - A Deep-Neural-Network-Based Seismic Arrival Time Picking Method ![python](assets/python.png)

## Seismic data access

- [EarthScope](https://ds.iris.edu/ds/nodes/dmc/data/) (formerly IRIS) - Waveform and Event data access, US based.
- [EIDA (ORFEUS)](https://orfeus-eu.org/data/eida/) - Waveform and Event data access, EU based.

## Seismic data handling

- [ObsPy](https://github.com/obspy/obspy/wiki/) - Python framework for processing seismological data ![python](assets/python.png)
- [Seismic Handler](https://www.seismic-handler.org) - Powerful seismic waveform analysis tool
- [Seismic Unix](https://github.com/JohnWStockwellJr/SeisUnix) - Seismic processing, research, and educational software package
- [Seis.jl](https://github.com/anowacki/Seis.jl) - Open, fast and flexible framework for analysing seismic data in Julia ![julia](assets/julia.png)
- [Snuffler (pyrocko)](https://pyrocko.org) - Seismogram browser and workbench ![python](assets/python.png)

## Seismic interferometry & ambient noise

- [MSNoise](http://www.msnoise.org) - Python package for monitoring using Ambient Seismic Noise ![python](assets/python.png)
- [NoisePy](https://github.com/noisepy/NoisePy) - Fast and easy computation of ambient noise cross-correlation functions ![python](assets/python.png)
- [noisi](https://github.com/lermert/noisi) - ambient noise cross-correlation modeling and inversion ![python](assets/python.png)
- [SANS](https://sans.ethz.ch) - Seismic Ambient Noise Source Maps
- [SeisNoise.jl](https://github.com/JuliaSeismo/SeisNoise.jl) - fast and easy ambient noise cross-correlation in Julia ![julia](assets/julia.png)
- [SeisMIC](https://github.com/PeterMakus/SeisMIC) - Seismological Monitoring using Interferometric Concepts ![python](assets/python.png)
- [WMSAN](https://tomasetl.gricad-pages.univ-grenoble-alpes.fr/ww3-source-maps/) - Wave Model Sources of Ambient Noise ![python](assets/python.png)

## Source localisation

- [acoular](https://www.acoular.org) - Acoustic testing and source mapping software ![python](assets/python.png)
- [beampower](https://github.com/ebeauce/beampower) - Beamforming (or backprojection) of seismic signal for event detection and location ![python](assets/python.png)
- [BPMF](https://github.com/ebeauce/Seismic_BPMF) - Earthquake detection and location with GPU-accelerated processing ![python](assets/python.png)
- [fast_beamforming](https://github.com/schipp/fast_beamforming) - Fast and efficient beamforming in Python ![python](assets/python.png)
- [HypoDD](https://www.ldeo.columbia.edu/~felixw/hypoDD.html) - Double-difference earthquake location algorithm
- [NonLinLoc](https://github.com/alomax/NonLinLoc) - Non-Linear Location

## Structure imaging

- [MSNoise-Tomo](https://github.com/ThomasLecocq/msnoise-tomo) - a plugin to the MSNoise framework for 2D tomography ![python](assets/python.png)
- [PyGLImER](https://github.com/PyGLImER/PyGLImER) - Workflow to create a global database for Ps and Sp receiver function imaging ![python](assets/python.png)

## Synthetic seismograms

- [AxiSEM](https://github.com/geodynamics/axisem) - Axially symmetric Spectral Element Method ![fortran](assets/fortran.png)
- [Computer Programs in Seismology](https://github.com/rbherrmann/ComputerProgramsSeismology) - a package of programs for making synthetic seismograms and for the inversion of seismic data
- [Fomosto (pyrocko)](https://pyrocko.org) - Calculate and manage Green’s function databases ![python](assets/python.png)
- [instaseis](https://instaseis.net) - Instant Global Seismograms Based on a Broadband Waveform Database ![python](assets/python.png)
- [Salvus](https://mondaic.com) - Waveform Simulations and Inversions
- [SeisSol](https://seissol.org) - A software package for simulating wave propagation and dynamic rupture
- [SPECFEM](https://specfem.org) - A family of open-source spectral-element method software codes for computational seismology.
- [SW4](https://github.com/geodynamics/sw4) - Seismic Waves, 4th order accuracy ![cpp](assets/cpp.png) ![fortran](assets/fortran.png)

## Synthetic travel times, ray parameters and ray paths

- [TauP](http://www.seis.sc.edu/taup/) - Seismic travel time calculator ![java](assets/java.png)
- [Cake (pyrocko)]((https://pyrocko.org)) - 1D travel-time and ray-path computations ![python](assets/python.png)
- [scikit-fmm](https://github.com/scikit-fmm/scikit-fmm) - Fast Marching Method for Python ![python](assets/python.png)
- [pykonal](https://github.com/malcolmw/pykonal) - Fast Marching Method in Cartesian or spherical coordinates in 2 or 3 dimensions ![python](assets/python.png)

## Visualisation

- [cartopy](https://scitools.org.uk/cartopy/docs/latest/) - Maps for matplotlib ![python](assets/python.png)
- [cmcrameri](https://www.fabiocrameri.ch/colourmaps/) - Scientific colour maps
- [cmocean](https://matplotlib.org/cmocean/) - Beautiful colormaps for oceanography
- [GMT](https://www.generic-mapping-tools.org) - Generic Mapping Tools
- [Paraview](https://www.paraview.org) - The world’s leading open source post-processing visualization engine
- [Scientific Visualization (open access book)](https://github.com/rougier/scientific-visualization-book) - Open access book
