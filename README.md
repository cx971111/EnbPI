## Description 
- Please see the [_main_ branch](https://github.com/hamrel-cxu/EnbPI/tree/main) on how the code should be used and what are included in the ICML conference version. The .py test files below are all written in Jupyter notebook format, so that they are meant to be executed line by line.
```
@ARTICLE{xu2023enbpi,
  author={Xu, Chen and Xie, Yao},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
  title={Conformal Prediction for Time Series}, 
  year={2023},
  volume={45},
  number={10},
  pages={11575-11587},
  doi={10.1109/TPAMI.2023.3272339}}
```
## Difference from earlier
  - **🌟🌟Include [Demo_code.ipynb](https://github.com/hamrel-cxu/EnbPI/blob/Journal_code/Demo_code.ipynb), which compares EnbPI, SPCI, Adaptive-CI, and NEX-CP WLS shown in Section 6.3 as a Jupyter notebook.🌟🌟**
  - Include [tests_simulation_journal.py](https://github.com/hamrel-cxu/EnbPI/blob/JMLR_code/tests_simulation_journal.py)
  - Delete test_paper.py, with [tests_paper+supp_journal.py](https://github.com/hamrel-cxu/EnbPI/blob/JMLR_code/tests_paper%2Bsupp_journal.py) containing everything to reproduce real-data results in the main text and in the appendix
  - Delete PI_class_ECAD.py, with [utils_ECAD_journal.py](https://github.com/hamrel-cxu/EnbPI/blob/JMLR_code/utils_ECAD_journal.py) containing all the functionalities.
  
## References
- Xu, Chen and Yao Xie (2023). Conformal prediction for time-series. *Journal version, IEEE Transactions on Pattern Analysis and Machine Intelligence.*
- Xu, Chen and Yao Xie (2021). Conformal prediction interval for dynamic time-series. *Conference version, The Proceedings of the 38th International Conference on Machine Learning, PMLR 139, 2021.*
- Xu, Chen and Yao Xie (2022). Conformal prediction set for time-series. *ICML 2022 Distribution-Free Uncertainty Quantification workshop.*
- Xu, Chen and Yao Xie (2021). Conformal Anomaly Detection on Spatio-Temporal Observations with Missing Data. *ICML 2021 Distribution-Free Uncertainty Quantification workshop.*
