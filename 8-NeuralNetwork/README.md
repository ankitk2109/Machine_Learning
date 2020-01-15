# Neural Network

Neural networks are a set of algorithms, modeled loosely after the human brain, that are designed to recognize patterns. They interpret sensory data through a kind of machine perception, labeling or clustering raw input. The patterns they recognize are numerical, contained in vectors, into which all real-world data, be it images, sound, text or time series, must be translated. Neural networks help us cluster and classify.

### Applying NN on Hotel Review Data:

![image](https://user-images.githubusercontent.com/26432753/72459173-1a246f80-37c2-11ea-9bf9-bdcc74aa6cfb.png)

** Holdout Testing **
1. Divide the data into train and test splits
2. Build multiple models with different stopping conditions (iterations)
3. Overfitting increases with training
4. Regularization (set alpha to say 5) stops overfitting.

![image](https://user-images.githubusercontent.com/26432753/72459245-450ec380-37c2-11ea-99fe-951902884dba.png)


### Two Moons Dataset:

Using synthetic data generated using make_moons - two dimensions, 100 samples.
Default MLPClassifier parameters:
  * 1 hidden layer, 100 units
  * learning_rate_init = 0.001
  * max_iter = 200
  * momentum = 0.9
  
Try different learning rates and different structures - 2 hidden layers with 10 or 100 nodes.  

![image](https://user-images.githubusercontent.com/26432753/72459399-9d45c580-37c2-11ea-9f09-beb4d1fde650.png)

Different random initialisations:

![image](https://user-images.githubusercontent.com/26432753/72459475-c1090b80-37c2-11ea-8c0b-651b257d0887.png)

### Diabetes Data
This analaysis on the diabetes data is included to show that the overfitting is not just a problem with the Hotel Review data.

![image](https://user-images.githubusercontent.com/26432753/72459554-f150aa00-37c2-11ea-888b-5aa3342eb5cf.png)

