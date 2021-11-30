# CMPE-255_S3-Group10
Git repository for CMPE255 Section 3 term project by Group 10. 

Group Members:

  1. Harshavardhana Reddy Namburu- 015920775 
  2. Niousha Noshiravani - 015963493 
  3. Pavan Karthik Gollakaram - 015945670 (Github username - pavankarthikg)
  4. Teja Ganapati Jaddipal - 015957526(Github username - gthreehosmane)


Steps to be followed:
1. Make sure that all required libraries are installed before running the .ipynb files
2. Clone the github repository to local machine. The repository also contains the entire dataset.
3. Upload the .ipynb files to jupyter notebook. Please update the path for the dataset in .ipynb files before running the notebook.
4. Authorship-Identification-Gridsearch.ipynb is the code for the project using approach 1 which makes use of GridSearch for best hyperparameters. It takes lot of time to run.
5. Authorship-Identification.ipynb is the code for the project using approach 2 which makes use of manual search for best hyperparameters.
6. Following are the few errors we faced and the solution for the errors.

  - If Spacy is not yet installed, run these commands:<br/>
      !conda install --yes -c conda-forge spacy <br/>
      !python -m spacy download en_core_web_sm
  - Install 'yellowbrick' extension
  >> conda install -c districtdatalabs yellowbrick
7. If you face an error like 'cannot import safe_indexing', it is because of the version mismatch of scikit learn. Resolve this with the below commands
      - conda remove scikit-learn
      - conda install -c conda-forge scikit-learn=0.23.2
8. If you get error for '.DS_store' and '.ipynb_checkpoints' files while running the code, please uncomment the line of code to remove those files in jupyter notebook.
<img width="1021" alt="Screen Shot 2021-11-29 at 10 56 17 PM" src="https://user-images.githubusercontent.com/13237444/144000421-4aca267c-83b7-4dd3-9321-4157632ab148.png">







References

1.  https://www.delftstack.com/howto/python/python-readlines-without-newline/
2.  https://stackoverflow.com/questions/3207219/how-do-i-list-all-files-of-a-directory
3.  https://docs.python.org/3/library/os.html
4.  https://www.tutorialkart.com/python/python-read-file-as-string/
5.  https://discuss.analyticsvidhya.com/t/how-to-calculate-the-accuracy-score-of-a-model-in-python/5622/3
6.  https://scikit-learn.org/stable/modules/model_evaluation.html
7.  https://scikit-learn.org/stable/modules/generated/sklearn.metrics.ConfusionMatrixDisplay.html#sklearn.metrics.ConfusionMatrixDisplay
8.  https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html#sklearn.metrics.confusion_matrix
9.  https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html#sklearn.metrics.classification_report
10. https://stackoverflow.com/questions/28200786/how-to-plot-scikit-learn-classification-report
11. https://scikit-learn.org/stable/auto_examples/text/plot_document_classification_20newsgroups.html#sphx-glr-auto-examples-text-plot-document-classification-20newsgroups-py
12. https://www.dataquest.io/blog/tutorial-text-classification-in-python-using-spacy/
13. https://www.analyticsvidhya.com/blog/2021/06/tune-hyperparameters-with-gridsearchcv/
14. https://www.mygreatlearning.com/blog/gridsearchcv/
15. https://medium.com/@cmukesh8688/sklearn-pipeline-gridsearchcv-54f5552bbf4e
16 https://matplotlib.org/stable/gallery/lines_bars_and_markers/barchart.html
17. https://stackoverflow.com/questions/35572000/how-can-i-plot-a-confusion-matrix
18. https://www.scikit-yb.org/en/latest/api/classifier/classification_report.html
19. https://stackoverflow.com/questions/28200786/how-to-plot-scikit-learn-classification-report

