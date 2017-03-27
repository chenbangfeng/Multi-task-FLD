Multi-task deep learning is about learning multiple tasks using shared representations in a supervisory environment. Existing multi-task learning methodologies rely on splitting the network at a particular layer depending on the task. They do not generalize well across various tasks. We explore the split architecture and cross-stitch unit on facial landmark dataset where we regularize weights to share representation by introducing a mutual weight regularization loss.

[Write-up](https://s3-us-west-2.amazonaws.com/georgegtan/final_report/nips16%20-%20Copy.pdf?response-content-disposition=inline&X-Amz-Security-Token=FQoDYXdzEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDHKXIqfwgb69RdyiRCKpAgAmBBZHMEI7IsGLcH%2B2t4uHU9v8mep%2FDPHVakCAhvvzPR8XblLc7W1ipImepT%2FqoYjKt61HcSu47M%2BGLdbNbkRZJswQMeuzgkdi3JsvosgrA2CH%2F9BN%2Bm3dMEQKnjyWEDvDaYMYZ7etsKvolo2kAGLa49HZSjyIL37zWpTaFMwhXz2U4T4kKmcL6%2FUl%2F%2BBvcYDywOOIi%2F5aRx3%2F6B7QyIBQQiS2z8lMI2Kl3MFYTcBfGEPmwiC79pbjic%2B4i5cMtxrkPg4h%2B4UDpmLGJkz5v8ail6nQOUSXU7iPZazfVjS25GlKfdnyepyY6SrCCNO%2FHQzjMnALO%2FbL2aeuR6ms9vhNN%2Bj%2FmSbqvdxpso1a49iNipJ8IDg1qSKG31eW6hNX8WRdQhfW%2BgNZkCjunuLGBQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20170327T040602Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAI2744YGHO6JCW25A%2F20170327%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Signature=380256e3ea43cd33b38b43de8a1d386fd6177692e89fe8ce28137b69d223859c)

[Poster](https://s3-us-west-2.amazonaws.com/georgegtan/mt_fld_poster.pdf?response-content-disposition=inline&X-Amz-Security-Token=FQoDYXdzEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDHKXIqfwgb69RdyiRCKpAgAmBBZHMEI7IsGLcH%2B2t4uHU9v8mep%2FDPHVakCAhvvzPR8XblLc7W1ipImepT%2FqoYjKt61HcSu47M%2BGLdbNbkRZJswQMeuzgkdi3JsvosgrA2CH%2F9BN%2Bm3dMEQKnjyWEDvDaYMYZ7etsKvolo2kAGLa49HZSjyIL37zWpTaFMwhXz2U4T4kKmcL6%2FUl%2F%2BBvcYDywOOIi%2F5aRx3%2F6B7QyIBQQiS2z8lMI2Kl3MFYTcBfGEPmwiC79pbjic%2B4i5cMtxrkPg4h%2B4UDpmLGJkz5v8ail6nQOUSXU7iPZazfVjS25GlKfdnyepyY6SrCCNO%2FHQzjMnALO%2FbL2aeuR6ms9vhNN%2Bj%2FmSbqvdxpso1a49iNipJ8IDg1qSKG31eW6hNX8WRdQhfW%2BgNZkCjunuLGBQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20170327T040517Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIAI2744YGHO6JCW25A%2F20170327%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Signature=f460c663f6ada6b7e2640e0749dcf605f7d1cf60d9a96071189591015c66b62b)

Citation:
 - https://github.com/luoyetx/deep-landmark
 - https://github.com/JeremyCCHsu/Kaggle_Facial_Keypoint
 - https://arxiv.org/abs/1604.03539

Data:
 - http://mmlab.ie.cuhk.edu.hk/projects/TCDCN.html
 - http://mmlab.ie.cuhk.edu.hk/archive/CNN_FacePoint.htm

Version:
 - Python v. 2.7.9
 - Tensorflow v. 0.11.0rc1