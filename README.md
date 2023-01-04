# Drug_Salt_Form_Detection
Drug Salt Form Dection is an NLP bassed Model which identifies all the drug salt form values present in a perticular Prescription Report.
Different techniques and libraries are used to create this model and detect the salt form values.
## Steps done to create this model are:
1. The first thing I did was installed spacy library (library we will use to detect all the medical entities).
2.Next thing I did was to import all the libraries which will be helpful throughout our model buolding .
3. Once libraries are loaded next what I did was loaded the dataset
4. After loading dataset I did used some Data Analysis techniques and cleaned , manupulated , discard all the unimportant part.
5. After this was done I created a list of all the sentences which are present in *introduction* column and extracted the positions of all the words which are salt form 
6. Once I got this list with position of each entity , I created Train Data which contained the *Introduction* and *Entity* which had the position of drug salt form in the introduction.
7. After I got the train data , I created an NLP Pipeline and Used it on my train data and got the value of losses
8. Once my NLP model is trained I tried it on text from the precription report and saw the result .
9. I saw most of the values my model detected were correct but there were some outliers .

## Result 
I performed this process which a small amount of dataset so the accuracy was low , as you increase the size of dataset , the accuracy also increases .
