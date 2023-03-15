# mrs-synth-spectra
## Synthesized Proton Spectra for Monte-Carlo Simulations
### Summary
These files represent brain proton spectra simulated in INSPECTOR for use in Monte-Carlo simulations for spectral fit error analysis.

The worksheet **FullWorksheetJanuary302021** contains the printout for the 30 different Monte Carlo simulations.

The nomenclature is MMOff is the imperfect model (i.e., MMs modulated by +/- 20%), and MMOn is the perfect model (i.e., the MM in the spectrum is exactly whats in the basis set).

The 3/8/20 Hz represents the 3/8/20 Hz<sup>2</sup> Gaussian broadenings used in the manuscript.

The basis set is in INSPECTOR format which can also be inspected in MATLAB.

Note that the basis set has been already Lorentzian and Gaussian broadened to match the 8 Hz<sup>2</sup> Gaussian broadening case.

Thus the extracted Gaussian broadening for the perfect model 3 Hz2 case should be -5 Hz<sup>2</sup>, and for the 20 Hz<sup>2</sup> case  should be 12 Hz<sup>2</sup>. For the imperfect case you will not get exactly these numbers because the model is imperfect.

### Resources
For more information, including relevant publications and other available downloads, please visit the MR SCIENCE Laboratory webpage at https://juchem.bme.columbia.edu/.
