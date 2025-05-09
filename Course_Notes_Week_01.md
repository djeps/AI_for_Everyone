AI value creation (by 2030, a McKinsey report)
in the SW industry
in other sectors
key question... is there a industry branch where AI hasn't had any impact of some sort yet or will never have
AI could broadly be generalized into:
ANI (Artificial-Narrow Intelligence)
basically everything AI-related in today's context (e.g. a self-driving autonomous vehicle)
every ANI example out there is what is usually referred to as a one trick pony
AGI (Artificial-General Intelligence)
and agent that mimics the human, does what a human is doing, learns and applies as a human would do
Most of the progress made is practically exclusively within the ANI segment of AI
There's a very large discrepancy between the progress made in ANI and AGI
To expect any meaningful progress in the latter, we would need a major technological breakthrough that will get us there and that simply is decades (at least!) if not centuries away! But who can say for sure!?
In any case, in today's context, when we say AI, it usually implies ANI
Most of the hype in ANI is due to the progress made in Deep Learning
Deep Learning is related to Neural Networks
One might say, that Deep Learning is (synonymous with) Neural Networks
A more accurate statement would be that the former is facilitated by or even accomplished through the latter
Rise of AI ~ (or largely driven by) Machine Learning or the progress made in ML
Most common type of ML is Supervised Learning
That is, learn A to B or map A to B (A -> B), where A is the input and B is the expected output
I personally would frame this: learn B from A which practically implies the same I believe. Either way, it's fine I guess
Examples:
input: audio -> output: transcript => application: speech recognition
input: email -> output: spam? => application: spam filtering
input: product image -> output: defect? => application: visual inspection
and many more...
Seems probably somewhat limiting, but in reality it's not i.e. there are huge benefits
Supervised Learning has been around. It's not a new concept but it has really taken off only recently
Why is that?
Like with many other AI applications, mostly due to two things: 1-big data and 2-big data processing (the HW to process that big data has improved a lot e.g. more powerful GPUs)
One additional significant factor would certainly be the rise of the neural network concept(s)
In traditional AI applications (specifically ML), as the amount of data increases, the performance of the system stagnates or saturates i.e. doesn't really improve over time
By implementing just a small (or shallow) neural network, the performance dynamics improves or keeps improving longer vs. traditional applications but it too eventually reaches saturation
Ultimately, by implementing a large (deep!) neural network, the performance dynamics improves drastically but it too will eventually saturate as the amount of available data increases (but here we are talking about big BIG data)
Hence, the naive way of thinking would be to keep enlarging the neural networks and as long as the amount of available data to learn from is there, the performance gain would be guaranteed!
Data... What is data? Data is whatever describes our system or adds meaning to the problem statement or the (business) use case - something from which we may derive our input and output. A data set would be a series of related data points represented ideally in a tabular form. Without data, moreover a significant dataset we would not be able to map A to B or input to output!
Acquiring data... How do we acquire our data or dataset? Well, mostly it depends on the circumstance and the use case e.g. what type of an AI enabled application are we developing? If we are to say develop an image recognition application that distinguishes cats from everything else, we might download 'a bunch' of images and manually label each one that is or contains a cat and all the rest. Or we may just download the dataset pre-labelled. This at least nowadays is extremely easy - again, depending on the use case. Another way to obtain data is from observing (recorded) user or system behavior. For example, we are trying to build an AI enabled application that facilitates predictive maintenance for a given machine or machines of the same type. One way of going about it, is to obtain a log of all the machine's parameters during operation and when it was in operation or in fault. In fact, if we obtain such data from all such machines from all production lines, we might use that data and build a model that predicts when one of those machines might be at faull and out of operation.
More data is certainly better than no data! But gathering data for the sake of gathering is a bad practice. Alas, garbage in - garbage out! We need valuable or meaningful data - data which might add value. This is one example of misuse of data.
Problems associated with data and dataset... mislabeled data, missing data, sometimes wrong data (let's not rule that one out), the presence of unstructured data such as audio, images, speech (things that humans easily process). Dealing with unstructured data, although impossible, requires special or at least different techniques of dealing with as opposed to those techniques involved with processing structured data (structured data is anything that could be presented in a nice and readable table or spreadsheet-like format!)
Machine Learning is not Data Science! The discipline of Data Science is usually employed as a tool within Machine Learning - especially in the preparation stage of datasets to be used by an ML algorithm. But in a more broader sense, it's the discipline that deals with analysing specific data sets and extracting insight from it. It is the "science of extracting knowledge and insights from data"! ML on the other hand, is the science or field of study that gives agents (e.g. computers) to learn and apply without programming any specific logic into them.
Deep Learning and Artificial Neural Networks (ANNs) imply the same and are used interchangeably! We need an ANN to implement a DL algorithm and map A to B or input(s) to output. An ANN is implemented with artificial neurons interconnected with each other. There's outer and inner or hidden layers (at least one for a shallow ANN) in any given ANN and what the network is in a less abstract way - because it certainly isn't magic - is one big mathematical formula that binds all the inputs to the output - through the artificial neurons! Although ANNs have certainly been inspired by human brains, the way they work has almost nothing to do with how a biological brain works.Finally, when we say a NN, we usually imply an ANN.
Any one time effort at successfully launching an AI project, doesn't make any company 'an AI company'. The company's overall strategy should be positioned and steered towards systematic and continuous gathering and processing of big data.
AI technology is certainly powerful and can bring a lot of positive impact, it can't do just about anything.
ML is quite suitable and capable of learning a simple concept... something that generally takes a human less than a second of thought to do with the assumptions there's plenty of data available
ML tends to do poorly when there's not enough data and it does miserably when trying to learn a complex concept. It also struggles with coping with new data samples - sample that 'jump out' from the given dataset with which the model was trained
