# Deep-Learning-Challenge
Solving a deep learning challenge using different types of GAN

They were 4 coding question where i should start from a simple GAN implementation and build up on it. [Here](https://github.com/amanchadha/coursera-gan-specialization/blob/main/C1%20-%20Build%20Basic%20Generative%20Adversarial%20Networks/Week%201/C1W1_Your_First_GAN.ipynb).

Note : The loss in the graph are calculated every time the code prints the images of the generator and discriminator also mean error for each question is calculated later.

Question one is running linear model with no weight normalization and here is the graph of the result:

<p float="left">
  <img src="Images/1 - Gen and Disc Loss Without BatchNorm.PNG" width="500" height="400" />
</p>

Question two is running linear model with batch normalization and here is the graph:

<p float="left">
  <img src="Images/2 - Gen and Disc Loss With BatchNorm.PNG" width="500" height="400" />
</p>

Question three is running 2D CNN layers and 2D Batch Normalization and here is the graph:

<p float="left">
  <img src="Images/3 - Gen and Disc Loss With 2D CNN and 2D BatchNorm.PNG" width="500" height="400" />
</p>

Question four is running 2D CNN layers and Spectral Normalization and here is the graph:

<p float="left">
  <img src="Images/4 - Gen and Disc Loss With Spectral Norm.PNG" width="500" height="400" />
</p>

And here is the mean error for each question:

| Question  | Generator loss  | Discriminator loss | Mean loss
| ------------- | ------------- | ------------- | -------------
| linear model with no weight normalization  | 1.6464909422397627  | 0.3170868508219722  | 0.98178889653087
| linear model with batch normalization  | 1.8335691130161285  | 0.20155112892389274  | 1.01756012097
| **2D CNN layers and 2D Batch Normalization**  | **0.583811241984368**  | **0.7356016211509696**  | **0.65970643156767**
| 2D CNN layers and Spectral Normalization  | 0.707224202632904  | 0.7075913230180738  | 0.70740776282549
