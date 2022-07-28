# LEOLens
Python software to perform near-field delay corrections to visibilities based on input 'assumed' range. 

Input Arguments
---------------
--ms : name of input measurement set  
--time : the timestep under consideration  
--debug : if true, prints out a lot of stuff  
--focus : the output focal distance of the array (km)  
--metafits : the metafits file of the measurement set  
--pcra : the ra (in deg) of the phase centre  
--pcdec : the dec (in deg) of the phase centre  


Note:- The roots and foundation of this package are based on many functions from [LEOVision](https://github.com/StevePrabu/LEOVision) and techniques developed in [Prabu et al 2022](https://www.sciencedirect.com/science/article/pii/S0273117722003763). However, LEOLens is also significantly different from LEOVision in many ways, such as being independent of input TLEs and being a more generic software that is capable of 'focussing' the aperture array to any assumed focal distance. Also, since LEOVision is already part of a published journal article (Prabu et al 2022), I wish to retain LEOVision as a separate (and frozen) software package for reproducibility purposes.
