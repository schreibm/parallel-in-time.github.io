---
layout: page_code
title: SWEET
date: 2018-04-29 11:45 +0200
navbar: Codes
subnavbar: sweet
logo: 
code_url: https://sweet.gitlabpages.inria.fr/sweet-www/
language: C++
developers:
  - name: Martin Schreiber
    lead_developer: true
  - name: Various others, see website
short_desc: Development written in C++, which allows us to study various PinT time integration and compare it to other time integration methods using global spectral methods in space.

---

Development written in C++, which allows the study of PinT time integration and compares it to other time integration methods using global spectral methods in space.

This C++ development supports the development of simulations using global spectral methods.
The main reason for using spectral methods is to reduce or fully avoid discretization errors in space and focus purely on time-integration issues for ODEs and PDEs.

A variety of time integration methods are supported. Regarding PinT methods, there are Parareal, rational approximation of exponential integrators (REXI), ML-SDC (based on libPFASST), PFASST, and MGRIT. 
