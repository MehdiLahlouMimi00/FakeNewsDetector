# FakeNewsDetector
A model that can actually predict if a news message is Fake or Real


For this project I have used the scikit-learn library with its common library set (pandas, numpy and itertools) to process the data and feed it to the model,  
The main features of this project are **TF** (terms frequency) and **IDF** (Inverse Document Frequency), combining them gives **TF-IDF**. According to [Wikipedia](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) :  
*TF* :   
the relative frequency of term t within document d  
*IDF* :  
measure of how much information the word provides, i.e., if it is common or rare across all documents  
  
`TfidfVectorizer` is the vector that will be containing all these necessary metrics  
  
  
The last important thing about this project are the **passive agressive classifiers**, that [GeeksForGeeks](https://www.geeksforgeeks.org/passive-aggressive-classifiers/) will explain better than me.  

The rest of the code is just basic coding with sklearn and its OOP approach.  

Thank you for your time !
