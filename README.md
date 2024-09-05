                                                              
# Stock Prediction by Mindaugas Brazionis


### 1.Description: 
I will predict stock prices using LSTM Model and test it on different stocks AMZN , Tesla , Apple


### 2 Model explanation:
 ## LSTM
<br>LSTM, or Long Short-Term Memory, is a type of artificial neural network used in machine learning, particularly for processing and making predictions based on sequences of data. It is a type of recurrent neural network (RNN) that is particularly good at remembering important information over long periods while forgetting less important details.

<br>In simple terms, you can think of LSTM as a smart memory system within a computer program that helps it understand patterns over time. For example, if you want to predict the future price of a stock based on past prices, LSTM helps the program remember the important patterns in those past prices to make a better prediction.


![image](https://github.com/user-attachments/assets/8e062f0a-a604-413b-90b6-e92819379f3e)


 ## GRU
<br>GRU, or Gated Recurrent Unit, is another type of neural network used for working with sequences of data, like time series or text. It's very similar to LSTM but a bit simpler and faster.

<br>Think of GRU as a streamlined version of LSTM. It also helps a computer remember important patterns in data over time, but it does this with fewer steps. While LSTM has a more complex memory system with multiple gates (like doors that control the flow of information), GRU has fewer gates, making it easier and quicker to use.


![image](https://github.com/user-attachments/assets/86d65e85-49be-4d22-8fbb-2851c9dff334)

## Transformers 


<br>Transformers are a type of neural network that has revolutionized the way computers understand and generate sequences of data, like text, speech, or even images. They are particularly well-known for their use in natural language processing tasks, such as translating languages, summarizing articles, or answering questions.

<br>Unlike LSTM or GRU, which process data step-by-step (like reading a book one word at a time), Transformers can look at the entire sequence all at once. This ability helps them understand the context and relationships between different parts of the data more effectively.

<br>In simple terms, think of a Transformer as a powerful tool that can quickly scan and understand an entire paragraph or even a whole book at once, rather than reading it line by line. This makes it much faster and better at capturing the big picture, especially when dealing with large amounts of data.


![image](https://github.com/user-attachments/assets/226b7b1e-0be9-4002-b8ff-3c8e8b5e91d2)



### 2.Dependencies: 
I will use these libraries and tools to run the code (e.g., torch, yfinance, numpy, etc.).


![Screenshot 2024-09-03 115535](https://github.com/user-attachments/assets/73238d24-f770-4c47-822c-891999fdfdd2)


3.Data Source: I use yfinance to retrieve data 

![Screenshot 2024-09-03 150344](https://github.com/user-attachments/assets/3066db2a-8380-4815-9720-89d703a60c57)




Preprocessing: 
<br>Data Retrieval: The function uses yfinance to download historical stock prices for a given ticker symbol over a specified period and interval.
<br>Data Processing: Dates and adjusted close prices are extracted from the downloaded data.
<br>Data Summary: The function prints the number of data points and the range of dates.
<br>Data Visualization: If plot=True, the function generates a plot of the adjusted close prices over time, with custom x-axis ticks and a title reflecting the stock ticker and date range.



## 5. First  try LSTM model with this parameters on Tesla stock 


![T](https://github.com/user-attachments/assets/cb831d7d-6b6c-45d6-ba81-425a0965cff4)


## Training proccess

![Tesla](https://github.com/user-attachments/assets/77974db9-bab5-4a11-b14a-31e3a3f09e2e)


## Ploting results 


![TESl](https://github.com/user-attachments/assets/1d65559b-9894-4a28-8541-3ac20949440e)




## AMZN Stock parameters
![Screenshot 2024-09-03 205616](https://github.com/user-attachments/assets/36c4dd59-4d74-4d47-b6e9-992db6380fae)

## Training proccess
![Screenshot 2024-09-03 205557](https://github.com/user-attachments/assets/4d06fd84-f6cf-4e21-8b49-98a5813f0c9f)

## Ploting results


![Screenshot 2024-09-03 213706](https://github.com/user-attachments/assets/d860e56b-5169-4290-87c4-a53a63140635)





