.. _spectra_code_ref:

SunPy spectra
=============

Overview
--------
The core classes in this package are Spectrum and Spectrogram. These representing
a spectrum as a specific point in time or one as a function of time, respectively.
Individual instruments are supported through subclasses. To see what instrument
are supported see :ref:`spectrum-classes` and :ref:`spectrogram-classes`.

.. warning:: This module is under development! Use at your own risk.

Spectrum
--------

.. automodapi:: sunpyspectra.spectrum

.. _spectrum-classes:

Spectrum Classes
----------------
None yet.

Spectrogram
-----------

.. automodapi:: sunpyspectra.spectrogram

.. _spectrogram-classes:

Spectrogram Classes
-------------------
There are a series of subclasses which are specialised for each
instrument.

.. automodapi:: sunpyspectra.sources
