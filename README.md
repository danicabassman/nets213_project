nets213_project
===============
The contents of the repository is fairly minimal since our project won't require any code. The issues contain mockups for our HITS and a description for our quality control and data aggregation models. 

The first two issues show sample setups for the first parts of the HITs, which act both as priming questions (for the experimental group) and as quality control questions. They contain sample questions using both words and images for priming and for the control and experimental groups. These also act as quality control questions since they have undisputed answers, so we know to only use data from workers who got these questions correct to rule out any workers that are randomly clicking. 

The third issue shows as a sample question for the second part of the HITs, and the responses to these are the ones we will be aggregating for data collection. We hope to show that the responses to these questions will change depending on if the workers were primed in part one. 

The fourth issue describes our quality control and data aggregation methods. The quality control is taken care of in the first part of the HITs (as described above), and our aggregation model is fairly simple--it involves averaging the responses to questions in part two of the HITs (i.e., "what would you be willing to pay for the product below?" or "how much is the product below worth?") and showing that there is statistically significant change in average reservation prices for a given product for workers that have been primed vs. those that have not been primed. We will also break averages down further into the method of priming (images vs. words). 

The fifth issue contains the set of 10 images that the primed group will see. For each image, the worker will be asked whether the picture contains a dog. Seven of the images contain a dog, all of the images have a luxury item or association. 

The sixth issue contains the set of 10 images that the control group will see. For each image, the worker will be asked whether the picture contains a dog. Seven of the images contain a dog, none of the images have a luxury item or association.

The seventh issue contains the set of 10 words that the primed group will see. Five of these words (Rolex, Ferrari, Mansion, Tahiti, and Fashion) have an association with luxury and wealth. The other five are just normal everyday words.

The eight issue contains the set of 10 words that the control group will see. It contains the same normal everyday words that the seventh issue contains, plus five more normal everyday words. 

We have not included code for QC and aggregation methods because that will all be included in the HITs or done in CrowdFlower. 

The first two issues from the mockup also act as QC questions, and sample output for them is very straight forward (both images do contain dogs, meteor has 3 syllables, rolex has 2 syllables). 

Data aggregation is a simple averaging of responses, so we did not include sample input/output.

We also did not inlcude a flow diagram because it did not seem applicable to our project. We will be designing HITs from our data and analyzing users' responses, so data flow is fairly straight forward. 

