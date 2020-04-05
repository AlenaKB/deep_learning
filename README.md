# deep_learning

I tried to implement a neural network to solve a classification problem
After trying out several methods, the best score I managed to achieve was 73

To increase the effectiveness of the model I attempted to look for potential outliers in the dataset. 
I found a algorithm called Isolation Forest that shows specifically outliers, because the 'ASK_AMT' column seemed suspicious
and I felt I need to check it. 
the algorithm showed I have over 5 thousand outliers there. Due to the lack of knowledge of the algorithm and its implementation, I decided to leave that idea for now. Although, if I did everythig correctly, 5k outliers is a lot and possibly that is the reason why my neural network just wasn't effective at all. 
Other than that, I tried several different ways of bucketing and received a somewhat similar score everytime. 

After tweaking the number of layers, and neurons, and the activation functions themselves (I deleted a couple, because that was getting ridiculous) I decided to try out a supervised learning algorithm, because in the end if the day we are dealing with classification here. 
The best result I managed to achieve after all, remained 73. 

