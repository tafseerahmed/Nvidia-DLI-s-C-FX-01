In short, a successfully trained neural network model is right as often as it needs to be to make it part of a viable solution. Let's take a second to expand on what that means.

The model that we have been training has been trained to classify images, specifically images of dogs and cats. In this case, a model that matched human intelligence (we could address superhuman intelligence but will hold off to retain focus) would agree with you every single time. For every image you would classify as a dog, it would classify as a dog. In this respect, performance would be measured in terms of accuracy, or percentage of images that were correctly classified. 

Other models will measure performance in slightly different ways. A model that specified the location of an object (localization) would aim to output locations as close to where the actual object was as possible. 

In general, performance in training is measured by how accurately a model aligns with the real world. You could imagine that the better your model performs, the more useful it will become. Eg. a model that can detect cancer as accurately as a radiologist will save lives for patients who did not have access to great medical care where a model that was less accurate would cause deaths.

In this next section, we will engage with some strategies for improving training performance using our existing model. You will learn:

To run more training epochs on an existing model, analogous to a human learner studying more.
To search the hyperparameter space, analogous to a human learner responding differently to a different teaching style.
To use the results of others' research, compute, network design, and data, analogous to a human learner copying off an expert
=====================================================================================================================================

 

If still waiting for the environment to start, explore the dataset we will be using in this section, imagenet.