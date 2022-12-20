# readme
Problem Statement/Applications
Visual Question Answering (VQA) system is an algorithm that takes an image and a natural language question about it as input and produces an accurate answer as the output. VQA represents not a single narrowly-defined problem but rather a rich spectrum of semantic scene understanding problems and associated research directions.
	Visual Question Answering provides user a more convenient and effective way to analyze any given image during work, study, data analysis, research and life. For instance, users can easily get the number of bullets on the battle field, count numbers of people between various races, capture those key information that the user wants to quickly obtain on the picture, quickly establish data pool based on given images and even set up human facial recognition system. Therefore, VQA system can save a huge amount of time and human resources.
Current Research
There are two main VQA Models
1.LSTM(Long short-term Model) + CNN Model
2.Hierarchical Co-Attention Model

LSTM is defined as long short-term model, which is a special type of recurrent neural network that could learn long and short term dependencies in data.
The below picture shows that the LSTM is consisting of four neural network layers which are interacting with each other.  

![image](https://user-images.githubusercontent.com/113282545/191381154-8a06eadf-7986-4207-a685-16daea09c4bd.png)









CNN Model is defined as convolutional neural network, which is a type of artificial neural network that specifically designed to process pixel data during image recognition and processing.
CNN Model is a combination of convolution layers, pooling layers fully connected layers

![image](https://user-images.githubusercontent.com/113282545/191381185-49756a3a-6da8-43fd-a475-71de38d6e9f6.png)


Current problem
Evaluating a VQA model correctly is a difficult problem. Testing sets always share the same distribution as the training sets. Therefore they always share the same biases or shortcuts. So currently, the mainstream of solution is to create out-of-distribution datasets. The OOD datasets are assumed that a biased model would fail to answer in rare cases, because it learned superficial correlations, while a correct model would manage to answer even in contexts that are different from its training set.
However, the correct evaluation with the out-of-distribution setup is still challenging because it does not match the usual assumptions made in machine learning. 
Also, the data-set creation is a challenging problem. It is hard to gather enough out-of-distribution data that are different from the training set.




![image](https://user-images.githubusercontent.com/113282545/208770468-4d840948-a861-4c12-816e-a277ba446378.png)
![image](https://user-images.githubusercontent.com/113282545/208770483-cd2c8a24-4681-4782-afa2-d109b88cec3b.png)
![image](https://user-images.githubusercontent.com/113282545/208770489-9587a9ea-345e-4af9-b347-64d4dc16aad8.png)
![image](https://user-images.githubusercontent.com/113282545/208770496-42381da7-ab48-444a-bd7b-9c46fad591e5.png)
![image](https://user-images.githubusercontent.com/113282545/208770501-1eb90e22-430a-4d0d-a942-5e309f248277.png)
![image](https://user-images.githubusercontent.com/113282545/208770508-c46f7c02-99a1-4779-8021-0dcabd972ffc.png)
![image](https://user-images.githubusercontent.com/113282545/208770517-10a7ac94-5b05-40ec-8fe2-b139a6a2fc1a.png)
![image](https://user-images.githubusercontent.com/113282545/208770526-1d05a4b5-9355-4bbd-a2b4-79b0ba6439db.png)
![image](https://user-images.githubusercontent.com/113282545/208770533-54a34fd9-4701-4914-9ebb-aea701145e52.png)
![image](https://user-images.githubusercontent.com/113282545/208770540-4744f5d1-3bfb-44be-885a-c421330eaf44.png)
![image](https://user-images.githubusercontent.com/113282545/208770556-591e33f9-5a8a-4a1c-ae50-7b23c832bc7e.png)




	
RESOURCE LINKS:	

1.https://sanghani.cs.vt.edu/research-project/visual-question-answering-vqa/
2.https://cdancette.fr/2020/11/21/overview-bias-reductions-vqa/
3.https://www.tutorialspoint.com/time_series/time_series_lstm_model.htm#:~:text=It%20is%20special%20kind%20of,layers%20interacting%20with%20each%20other.
4.https://insightsimaging.springeropen.com/articles/10.1007/s13244-018-0639-9/figures/











