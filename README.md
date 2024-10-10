1. The `annotation_example` demonstrates the data format used for training. It is a JSON file generated from a `.txt` file after being annotated by the PIAT algorithm. For more details on the PIAT algorithm, refer to the paper available at: [https://ieeexplore.ieee.org/document/9780554/](https://ieeexplore.ieee.org/document/9780554/).

2. The `Train_set` is used to store the training data, while the `Test_set` contains the data for validation. Both files are in the aforementioned JSON format, and their filenames follow the convention "DiseaseName_PatientID".

3. The `disease_classification_name.xlsx` is a file used for the standardization of diagnostic names for respiratory diseases.

4. The `clinical_features_synonym.xlsx` is a file used to standardize the clinical features for LungDiag.
