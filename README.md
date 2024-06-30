Description of fitness tracker that can classify various barbell exercises:
1. Data folder there's file that reads all the seperated CSV files, processes them and merge them into a dataframe
2. Visualization folder is folder which holds a file that visualize all the data
3. Features is the folder that contains features such as
   - Outliers remover (outliers_remove.py file)
   - Repetition counter (count_repetitions.py file)
   - Butterworth lowpass filter, KMeans clustering, Temporal Abstraction and PCA (build_feature.py file)
4. Models is the folder for all the machine learning models that i created.
