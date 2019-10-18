# logistic-regression-with-cancer-dataset


we have a data set containing some medical history information for patients at risk for cancer. This data has been split into various training, testing, and validation sets; each set is given in CSV form, and is divided into inputs (x) and outputs (y).

Each patient in the data set has been biopsied to determine their actual cancer status. This is represented as a boolean variable, cancer in the y data sets, where 1 means the patient has cancer and 0 means they do not. You will build classiﬁers that seek to predict whether a patient has cancer, based on other features of that patient. (The idea is that if we could avoid painful biopsies, this would be preferred.)

Input data has three features: 
• age: Patient age is stored as a ﬂoating-point value, to give ﬁner-grained detail than simply number of years. 
• famhistory: A boolean variable indicating whether or not a patient has a family history of cancer (as usual, 1 = true, indicating that the family does have a cancer history).
• marker: A measured chemical marker that clinicians believe may have some correlation with the presence of cancer.

We will explore this dataset with logistic regresion model and visualize the performance to discuss about confusion matrix, threshold, parameter C( inverse penalty strength) and so on.
