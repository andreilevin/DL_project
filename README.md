# **Teaching** **Neural** **Networks** to Play SET 

The goal of this project was to train neural networks to classify features of playing cards in the game SET (rules explained [here](https://www.setgame.com/sites/default/files/instructions/SET%20INSTRUCTIONS%20-%20ENGLISH.pdf)).   To source my data, I took 50+ photos of  SET hands in different conditions (varying lighting, angle, background, etc.)  and used computer vision tools to extract an image of each individual card present.  After labeling and augmenting my image data, I used keras in tensorflow to train convolutional neural networks to classify SET cards by shape, color, number, and shading.   My image extraction script can be found in the jupyter notebook [card_extract_and_label.ipynb](https://github.com/andreilevin/DL_project/blob/main/card_extract_and_label.ipynb), while the neural network notebook is named [models.ipynb](https://github.com/andreilevin/DL_project/blob/main/models.ipynb).  The presentation slide deck is available [here](https://github.com/andreilevin/DL_project/blob/main/AndreiPresentation.pdf).



<img src="https://raw.githubusercontent.com/andreilevin/DL_project/main/mvp_figs/fig4.png"  width="600" />  


