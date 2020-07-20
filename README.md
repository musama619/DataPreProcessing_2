# Data-Preprocessing


# Data Preprocessing <br>

* ### Handling Missing Data <br>
* ### Encoding Independent Variables <br>
    *OneHotEncoder* <br>
* ### Encoding Dependent Variable <br>
    *LabelEncoder* <br>
* ### Train - Test Split <br>
* ### Feature Scaling <br>
    *Standardisation*
    
## Note: 
#### 1. Standardisation :  values between -3 and 3 (works all the time)
####  2. Normalisation : values between 0 and 1 (recommended only when features follows normal distribution)

![scaler](https://user-images.githubusercontent.com/34093998/87575874-01056880-c6ea-11ea-919d-99aaacd2b73d.PNG)

- remember to apply feature scaling after train test split
- feature scaling does not need to be applied on dummy variables as they already have values between -3 and 3

Important link: 
- https://medium.com/@contactsunny/label-encoder-vs-one-hot-encoder-in-machine-learning-3fc273365621#:~:text=What%20one%20hot%20encoding%20does,which%20column%20has%20what%20value.&text=So%2C%20that's%20the%20difference%20between%20Label%20Encoding%20and%20One%20Hot%20Encoding.

Data Preprocessing part 2: https://github.com/musama619/DataPreProcessing
