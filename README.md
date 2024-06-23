# Cs-137_Visualization

Using a radioactive element Cs-137 point source, PET imaging calibration can be conducted. The gamma energy emitted by Cs-137 is converted to the light energy proportional to it by the scintillation detector. The output signals are in the form of X, Y, and Z, where X and Y are the estimated 2D position of the scintillation event, while Z is the total light output in the crystal. By analyzing the spatial distribution of pulse heights, the location of one scintillation event (X, Y) can be identified.

An energy histogram is first plotted to identify the energy peak of the element. An energy window is applied at the energy peak region of +/- 10%, and the crystal segmentation was plotted based on that. The location of the scintillation crystal that has a higher pulse height is represented by a lighter colour, while that of a lower pulse height is represented with a darker colour. Lastly, the pixel value to the index location graph is plotted to identify the locations where the pixel values are high or low.
