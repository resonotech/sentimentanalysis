# sentimentanalysis
We collected these reviews from various social media forums. First, we collected sentiments and removed their html tags. After sentiment collection, three reviewers independently marked the polarity of each sentiment as positive or negative. The reviewers were computer science students and active users of social media. The average length represents the number of words in a sentiment. On average, a sentiment consists of single sentence with multiple sub-clauses. The maximum voting algorithm was used to select the final polarity of sentiment out of three votes. 
In Romanized Urdu, some words consist of multiple spaces. For example, “kay lay” (therefore) is one complete word but separated by a space. In the pre-processing stage, the boundaries of words are marked such that the algorithm could ignore the spaces and consider two words as one word. We adopted XML syntax to mark the boundaries. In the dataset, these words are enclosed in an XML tag as <word> kay lay </word>. 
