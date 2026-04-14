# phenanthrene_2H2O_tdc_data

tdc_homo_57_lumo58_full_available_pair_i_j_component_tdcs.csv  
Provides the time-derivative couplings between states i and j  (for states between 54 and 62, and we ignore i==j)

The header of the file provides the timestep index (base 1) , time /fs,  the total tdc coupling summed 1/ps, then the tdcs for each atom and cartesian coordinate.   
Since we did not calculate the electron-phonon coupling for the H atoms on phenanthrene, these are replaced with NaNs  
The couplings are phase corrected

tdc_homo_57_lumo58_full_available_raw_phase_pair_i_j_component_tdcs.csv  
Same but the couplings are not phase corrected.

tdc_homo57_lumo58_full_available_state_energies.csv  
Provides the eigenstate energies from FHI-aims for the states we are interested. 

the data inside water1/ is the same, except we only show the atoms related to water 1



