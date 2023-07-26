# 2CAHE_MFM_analysis
Magnetic force microscopy (MFM) analysis used in my PhD project on the two channel anomalous Hall effect (2CAHE) in SrRuO3 thin films.

This analysis is used in my thesis, and is similar to the analysis used in the Physical Review Materials paper https://doi.org/10.1103/PhysRevMaterials.4.054414.

The example data shows an ultra thin film of the ferromagnetic oxide SrRuO3. These films can show interesting peaks in the Hall effect in the ultra-thin limit. This Hall peak is often interpretted as a topological Hall effect resulting from chiral spin textures such as skyrmions. In my work we argue that the films are comprised of separate 4 and 5 unit cell thickness regions as a result of step-flow growth, and these two regions have opposite anomalous Hall coefficients which sum together to give a Hall peak. This MFM analys shows the films are comprised of two spatially separated magnetic regions, whose coercive fields match the steps in the Hall effect. Additionally I show that we cannot easily attribute the Hall peak to a THE which depends on the number of magnetic domains, versus an anomalous Hall effect which depends on the relative areas of domains.

This analysis is written in Python, and I use a Jupyter notebook. The libraries 'cv2' and 'pySPM' are not included with Anaconda by default.

Please contact me graham.kimbell at unige.ch if you have any questions about this work, or want to use any of the code etc., I'm happy to help.

Note: In cell 13 I manually add a custom legend for the histograms in Illustrator after this rendering, as the Python legend would be too large. The green curve is the 200 mT scan and the purple is the 4000 mT scan.
