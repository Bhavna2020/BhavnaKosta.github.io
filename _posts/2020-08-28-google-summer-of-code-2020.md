---
layout: post
title: Google Summer of Code 2020
date: 2020-08-28
description: A summary of work done in Google Summer of Code 2020. 
fig-caption: 
tags: 
---

A summary of work done - Google Summer of Code 2020

<!--excerpt-->

## [Project](https://summerofcode.withgoogle.com/projects/#5651188063666176)

### Title - General Printer Application SDK.

MENTORS -
[Ira McDonald, Till Kamppeter, Dheeraj, Michael Sweet, Danny Brennan]

I have contributed to development of [PAPPL](https://github.com/michaelrsweet/pappl) (Printer Application Framework).

*PAPPL is a simple C-based framework/library for developing CUPS
Printer Applications, which are the recommended replacement for
printer drivers.*

I have also developed the [HP Printer Application](https://github.com/michaelrsweet/hp-printer-app)

-------------------------------------------------------------------------------------------
## DNS-SD Discovery Support in PAPPL

Support for printer discovery and lookup using mDNS/DNS-SD(for pdl-datastream) (AppSocket/JetDirect).

[Related Issue](https://github.com/michaelrsweet/pappl/issues/18) - Closed

Closed by:

- [Pull Request 1](https://github.com/michaelrsweet/pappl/pull/24) - Merged

- [Pull Request 2](https://github.com/michaelrsweet/pappl/pull/29) - Merged

-------------------------------------------------------------------------------------------
## SNMP Discovery Support in PAPPL

Support for printer discovery and lookup using SNMP.

[Related Issue](https://github.com/michaelrsweet/pappl/issues/17) - Closed

Closed by:

- [Pull Request](https://github.com/michaelrsweet/pappl/pull/31) - Merged

-------------------------------------------------------------------------------------------
## papplMainloop in PAPPL

Standard command-line interface for PAPPL-based printer applications.

[Related Issue](https://github.com/michaelrsweet/pappl/issues/19) - Closed

Closed by:

- [Pull Request](https://github.com/michaelrsweet/pappl/pull/26) - Merged

-------------------------------------------------------------------------------------------
## Porting Example of CUPS rastertohp in PAPPL

[HP Printer app](https://github.com/michaelrsweet/hp-printer-app) - Example printer application for the CUPS rastertohp filter and corresponding PPD files (laserjet.ppd, deskjet.ppd, and generpcl.ppd).

[Related Issue](https://github.com/michaelrsweet/pappl/issues/16) - Closed

Closed by:

- [Pull Request](https://github.com/michaelrsweet/pappl/pull/32) - Merged

-------------------------------------------------------------------------------------------
## Snapcraft and systemd support in HP Printer Application

Snapcraft packaging template and systemd service support.

[Related Issue](https://github.com/michaelrsweet/pappl/issues/16) - Closed

Closed by:

- [Pull Request](https://github.com/michaelrsweet/hp-printer-app/pull/1) - Merged

-------------------------------------------------------------------------------------------
## Documentation and Design Notes - HP Printer Application

Documentation for converting PCL driver to a Printer Application.

[Related Issue](https://github.com/michaelrsweet/pappl/issues/16) - Closed

Closed by:

 - [Pull Request](https://github.com/michaelrsweet/hp-printer-app/pull/2) - Merged

-------------------------------------------------------------------------------------------
## Device Auto-Setup in PAPPL

Auto addition of nearby devices supported by a Printer Application.

[Pull Request](https://github.com/michaelrsweet/pappl/pull/36) - Open

-------------------------------------------------------------------------------------------
## Move rastertops filter functionality to filter function

Move the core functionality of rastertops filter into libcupsfilters so that it can be called directly.

[Pull Request](https://github.com/OpenPrinting/cups-filters/pull/282) - Merged

-------------------------------------------------------------------------------------------
## Move rastertopdf filter functionality to filter function

Move the core functionality of rastertopdf filter into libcupsfilters so that it can be called directly.

[Pull Request](https://github.com/OpenPrinting/cups-filters/pull/288) - Merged

[Pull Request](https://github.com/OpenPrinting/cups-filters/pull/289) - Merged

