# Quantifying-Complexity

I implement an information-geometric measure for the complexity of a system. We then test this measure in the context of an embodied cognitive agent.

This is a result of the work I did during my summer REU at the Santa Fe Institute under Dr. Nihat Ay and Dr. Keyan Ghazi-Zahedi. 
The code is all written in Julia, a scientific computing language with syntax similar to Python and performance closer to C++.

The code performs an information decomposition of multivariate mutual information into redundant, unique, and synergistic information. Complexity is then quantified as the total synergistic information in the complex system going from time step A to time step B. The formalization, intuition, and application of the measure is outlined in my Thesis paper from the summer internship, which I will upload shortly.

Further details regarding this measure can be found in the following papers:
* Keyan Ghazi-Zahedi, Carlotta Langer, Nihat Ay (2017): Morphological computation - Synergy of body and brain
* Paolo Perrone, Nihat Ay (2016): Hierarchical quantification of synergy in channels
* Paolo Perrone, Nihat Ay (2016): Iterative Scaling Algorithm for Channels
* Nihat Ay, Eckehard Olbrich, Nils Bertschinger, Jürgen Jost (2011): A geometric approach to complexity
* Imre Csiszár, Paul Shields (2004): Information Theory and Statistics- A Tutorial
