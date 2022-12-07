# Supplementary information for computational vibrational spectroscopy of BaZrS<sub>3</sub>

File structure:
* Figure_1.ipynb - Jupyter Notebook that calculates Gibbs free energies of degradation of the perovskite to the three Ruddlesden-Popper phases using the [ThermoPot code](https://github.com/NU-CEM/ThermoPot). 
* raw_data - folder containing data that is used to replot all the results presented in the study. 
  * binary
    * list of all binaries 
      * hse06 - HSE06 single point calculation output file containing total energies and bandgaps(relaxed geometry from PBEsol) 
      * phonon -
          *  phonon files used to plot the Raman spectra using [Phonopy-Spectroscopy](https://github.com/JMSkelton/Phonopy-Spectroscopy). 
          *  Raman plots with an assigned peak widths of 0.5cm<sup>-1</sup>
          *  NOTE: the folders that do not contain a Raman.yaml file are not Raman active materials. 
  * ternary (same file structure as that of binaries)
      
 
    
