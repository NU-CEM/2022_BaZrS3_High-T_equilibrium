# Supporting code and data for `High temperature equilibrium of 3D and 2D chalcogenide perovskites`
Find the paper [here](https://doi.org/10.1002/solr.202201078)

Note: 
- to run the Jupyter Notebooks you will need:
     - the standard Python scientific stack (pandas, numpy, matplotlib)
     - the [ThermoPot code](https://github.com/NU-CEM/ThermoPot) code
     - for `Ternary_phase_diagram.ipynb` you will also need [pymatgen](https://pymatgen.org/)
- [Phonopy-Spectroscopy](https://github.com/JMSkelton/Phonopy-Spectroscopy) can be used to plot the Raman spectra
- the folders that do not contain a Raman.yaml file are not Raman active materials

File structure:
* GFE_temperature.ipynb - Jupyter Notebook to calculate the Gibbs free energies of degradation from the 3D perovskite to the Ruddlesden-Popper phases (Figure 1)
* Ternary_phase_diagram.ipynb - Jupyter Notebook to construct a ternary phase diagram for Ba-Zr-S (Figure S4)
* raw_data - folder containing input and output files for first-principles calculations
  * binary
    * list of all binaries 
      * hse06 - HSE06 single point output file containing total energies and bandgaps (using relaxed PBEsol geometry) 
      * phonon -
          *  input files for plotting Raman spectra
          *  Raman plots with an assigned peak widths of 0.5cm<sup>-1</sup>
  * ternary (same file structure as that of binaries)

      
 
    
