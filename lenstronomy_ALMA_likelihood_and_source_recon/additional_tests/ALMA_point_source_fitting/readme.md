<img src="https://raw.githubusercontent.com/nanz6/projects_of_strong_lensing/main/lenstronomy_ALMA_likelihood_and_source_recon/additional_tests/ALMA_point_source_fitting/result%20unlensed%20point%20source.png" width="33%" alt="result_unlensed_ps.png"><img src="https://raw.githubusercontent.com/nanz6/projects_of_strong_lensing/main/lenstronomy_ALMA_likelihood_and_source_recon/additional_tests/ALMA_point_source_fitting/result%20ps%20source%20galaxy.png" width="33%" alt="result_ps_source_galaxy.png"><img src="https://raw.githubusercontent.com/nanz6/projects_of_strong_lensing/main/lenstronomy_ALMA_likelihood_and_source_recon/additional_tests/ALMA_point_source_fitting/result%20quadruply%20imaged%20quasar.png" width="33%" alt="result_quadruply_imaged_quasar.png">

Fitting results of fitting simulated ALMA observations with lenstronomy point sources in three cases: **unlensed point sources** (left), **point-source source galaxy** (middle), and **quadruply imaged quasar** (right). The plots show overall good parameter estimation using the ALMA image-plane likelihood function.

Parameter explanation: 
 - Left:
   - Unlensed PS Positions: Positions (x and y) for unlensed point sources.
   - Unlensed PS Amplitudes: Amplitudes of each unlensed point source.
 - Middle:
   - Lens params: Parameters of the lens profile.
   - PS source position: Position (x and y) for the source modeled as a point source.
   - PS source amplitude: Amplitude for the source modeled as a point source.
 - Right: (For the quadruply imaged quasar fitting, the positions of the four lensed PS images are free parameters, and some lens and source parameters are therefore derived from these positions. These parameters are listed as the "Solved nonlinear lens and source params" below.)
   - Independent nonlinear lens and source params: The independent, nonlinear parameters of the parametric lens and the Sersic source profile.
   - Solved nonlinear lens and source params: The non-independent parameters of the parametric lens and source profiles that are inferred through a nonlinear solver from the point source lensed positions.
   - Sersic Amplitude: The amplitude of the Sersic source profile.
   - Point source lensed positions: The lensed positions of the point source (the quasar), which are treated as free parameters during the fitting.
   - Point source amplitude: The amplitude of the point source.
