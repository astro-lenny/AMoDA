# Term paper: Tensorflow

This folder contains everything I worked with when experimenting. It is important to note, that most of the code is based on code by Lukas Rinder (https://github.com/LukasRinder/normalizing-flows/, the folder `normalizing-flows`), so the credit for the implementation of the different papers goes to him, while my contribution was in tweaking the architectures (mainly NSF) to the problem of building a classifier for RR Lyrae stars. The paper can also be found here.

Notebooks for the corresponding exercises:

  * Exercise 1:
      - FINAL_SOLUTION_NSF-R_4L_64B.ipynb
      - Exercise_1_plotting_alternatives.ipynb
  * Exercise 2:
      - FINAL_SOLUTION_NSF-R_4L_64B.ipynb
  * Exercise 3:
      - FINAL_SOLUTION_NSF-R_4L_64B.ipynb
      - ROC_all.ipynb
        (only loads fpr-, tpr- and auc-data from the other notebooks, saved in the stars_*** directories when notebooks were executed)
  * Appendix A and B:
      - all other notebooks (NSF-..., RealNVP, MAF-...)
      - NSF-F_4L_64B.ipynb (extra for sampling with flipping and rotating permutation)
      - sample_all.ipynb
        (compares samples from different architectures, saved when the corresponding notebooks were executed)
