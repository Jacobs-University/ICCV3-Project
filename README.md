
Data Set:

The data used in this project - “Mini-ImageNet” dataset. We have used this
dataset as mentioned in our research paper “Few-Shot Image Recognition with
Knowledge Transfer, 2019”. It contains five files having training, testing and
validation dataset. We have used the dataset which is in .PICKLE format in our
implementation. The link to download the dataset is given as below:
https://mega.nz/file/rx0wGQyS#96sFlAr6yyv-9QQPCm5OBFbOm4XSD0t-HlmGaT5GaiE


The Few-Shot learning model proposed is defined
as Knowledge Transfer Network (KTN). As mentioned above, this model combines 
visual feature learning, knowledge inferring and classifier learning into a
single unit framework. Furthermore, a Convolutional Neural Network (CNN) is
built in order to extract important features. This CNN model trains the visual
feature extracted by optimization of cosine similarity with the base categories of
the training dataset.

Implementation for a new dataset:

• In order to run a new dataset in this code, it should be the same format as
the mini Image dataset. Dataset should be as follow:
– Dataset_train_phase_train.pickle
– Dataset_train_phase_val.pickle
– Dataset_train_phase_test.pickle
– Dataset_val.pickle
– Data_test.pickle
Then by specifying the correct path on the code it is possible to execute
the code. All the data should be converted to “.pickle” format before
implementing the code.


• In order to run the testing using Vision-Knowledge Classifier, we can
specify the correct path of knowledge-based classifier model on the code
and upload it on the code to test it using the models trained for feature
extractors with CNN.
