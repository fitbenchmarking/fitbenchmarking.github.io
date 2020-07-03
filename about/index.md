---
layout: page
title: About FitBenchmarking
tags: [about]
date: 2016-11-22
comments: false
---

## What is FitBenchmarking?

FitBenchmarking is an open source Python package that was developed to compares how different nonlinear least squares software fitting packages perform on various fitting problems. The original version was written to perform this task with the widely adopted neutron data reduction software [Mantid](https://www.mantidproject.org).

Scientists, such as users of the ISIS Neutron and Muon Source, spend a large amount of their time fitting (optimizing) models against data. The ‘engines’ that do this are called minimizers.

Existing software that depends on fitting use a spectrum of minimizers and/or different implementations of the same minimizers. The FitBenchmarking package is  a tool that compares how implemenations of minimizers perform against common fitting problems.

## Why is FitBenchmarking important?
Fitting a mathematical model to data is a fundamental task across all scientific disciplines. (At least) three groups of people have an interest in fitting software:

* Scientists, who want to know what is the best algorithm for fitting their model to data they might encounter, on their specific hardware;
* Scientific software developers, who want to know what is the state-of-the-art in fitting algorithms and implementations, what they should recommend as their default solver, and if they should implement a new method in their software; and 
* Mathematicians and numerical software developers, who want to understand the types of problems on which current algorithms do not perform well, and to have a route to expose newly developed methods to users. 

Representatives of each of these communities have got together to build FitBenchmarking. We hope this tool will help foster fruitful interactions and collaborations across the disciplines.

## Contact and acknowledgements
For more install, technical information etc., please see the FitBenchmarking [documentation](https://fitbenchmarking.readthedocs.io/en/latest). 

This is a community package. We, of course thank ourselves:-), i.e. those who has and will contribute to the package, but in additional, to date, also we also would like to acknowledge funding from:

* EU [SINE2020](https://www.sine2020.eu) WP-10, which received funding from the European Union's Horizon2020 research and innovation programme under grant agreement No 654000
* STFC’s [ISIS Neutron and Muon Facility](https://www.isis.stfc.ac.uk) and STFC department
* STFC’s [Scientific Computing Department](https://www.scd.stfc.ac.uk)
* [Diamond Light Source Ltd](https://www.diamond.ac.uk)
* The Ada Lovelace Centre (ALC). ALC is an integrated, cross-disciplinary data intensive science centre, for better exploitation of research carried out at our large scale National Facilities including the Diamond Light Source (DLS), the ISIS Neutron and Muon Facility, the Central Laser Facility (CLF) and the Culham Centre for Fusion Energy (CCFE)

Finally, for questions, requests etc. don’t hesitate to contact us on support@fitbenchmarking.com, submit [Github issues](https://github.com/fitbenchmarking/fitbenchmarking/issues), join our weekly Friday FitBenchmarking Zoom catch-ups (please email support@fitbenchmarking.com to get details) or contact individual active developers.


