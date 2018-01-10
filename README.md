# TV-Script-Generation
Utilize TensorFlow and scripts from the Simpson's to create a recurrent neural network that can generate new scripts for scenes in Mo's Tavern.

## The Data
The data was made up of Simpon's scenes occuring exclusively in Mo's Tavern. Below is some data.

Dataset sample:

![alt text](https://github.com/SrahSrah/TV-Script-Generation/blob/master/tv-script%20dataset.png)

Results:

![alt text](https://github.com/SrahSrah/TV-Script-Generation/blob/master/tv-script%20results.png)

## Results
As we can see, the results are pretty non-sensical. This is because we trained on less than a megabyte of text. However, there are some encouraging signs that the model presented here is beginning to learn the basic structure of a script scene. The model is begining to place character names at the begining of lines followed by a colon. Likewise, there are a few phrases that could conceivably be in a real scene ("and take that Marge Simpson!"), along with referances to beer and drinks. 
