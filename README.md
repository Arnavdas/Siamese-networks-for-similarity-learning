# Siamese-networks-for-similarity-learning
Used a siamese network to learn about similarities and differences between different letters in different languages

- This code has borrowed a lot of ideas from this repo : https://github.com/akshaysharma096/Siamese-Networks and the medium article : https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d
- The idea of using of N-way single shot learning is a very good fit for this kind of learning beacuse perhaps similarity doesn't demand precise results
- The single shot method implementation here is a bit different from the repo, to understand the concept you could refer the medium article mentioned above
- I used graph plots as the evaluating metric beacause i didn't find much merit in describing it in a single number beacuse  we are depicitng similarities and differences and not how exactly are 2 different images are different and also i could not find a viable metric(like mean/median/precision) to describe the degree of similarity.
- The above point is somewhat hazy, siamese networks use the single shoy learning method to determine the similitude of differences of all the images in a batch so the number can be described best when it's amongst the batches
