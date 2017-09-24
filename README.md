# homework0
Please write about a deep learning expert in your README.md.
he/she can be a professor (e.g., Yann LeCun), a Ph.D student (e.g., Joseph Chet Redmon), a hacker (e.g., Flood Sung), a researcher (e.g., John Schulman), an enginner (e.g., Soumith Chintala), an entrepreneur (e.g., Matthew Zeiler), etc.
To avoid writing the same person, please report the person's name in  
https://docs.google.com/spreadsheets/d/153XruMO7DPONzBTkxh8ZoYSto1E_2zO021vs0prWZ_Q/edit?usp=sharing
First come first serve!
-------
Write here

# Dr. Fei-Fei Li

# Motivation
When I was a freshman, I liked to watch TEDs. One day, while browsing videos, I saw a Chinese woman talking about AI. Most of the talk was quite ordinary. However, I was shocked by the ending. I've already had a passion in neural network since high school, but what I didn't know was that AI already had the ability to describe the content of a picture. It was unbelievable for me at that time, even somewhat today. Years later, the part of the video I mentioned as "ordinary" isn't ordinary at all. It is the development of ImageNet. Dr. Fei-Fei Li is one of the people who makes me get involved in DL. Here's the TED Talk.
https://www.ted.com/talks/fei_fei_li_how_we_re_teaching_computers_to_understand_pictures?utm_campaign=tedspread--b&utm_medium=referral&utm_source=tedcomshare

# Short Biography
16: Move to U.S.. Although her parents are well educated, they can't speak English. She have to learn from scratch. All of them have to work really hard. She works in Chinese restaurants and cleans houses. Her high school teacher helps her a lot.

18: Receive nearly full scholarship from Princeton. Buy a dry cleaner for their parents in order to start a dry cleaning business.

22: Obtain B.S. degree in physics from Princeton University with High Honors during a huge bull market. Although get offers from Wall Street, she decides to go to Tibet to do a year of Tibetan medicine research.

29: Obtain master and Ph.D. degree in EE from Caltech. Her advisors are Pietro Perona and Christof Koch.

# ImageNet
What is it?

A labeled image database organized according to the WordNet (only objects). WordNet groups synonyms as "synsets", provides short definitions and usage examples, and records a number of relations among these synsets. In ImageNet, they aim to provide an average of 1000 images for each synset.

How is it built? Crowdsourcing!

Amazon Mechanical Turk is a crowdsourcing marketplace of human intelligence tasks (HITs). First, the Turks (workers) have to pass a definition quiz of a tag. After that, they can start deciding whether some images correspond to that tag which helps them earn some money.

# Deep Visual-Semantic Alignments for Generating Image Descriptions
Dr. Andrej Karpathy and Dr. Fei-Fei Li have trained a model that can generate a sentence from an image (image captioning). This is the researh which Dr. Fei-Fei Li introduced in TED. About the architecture, instead of adding softmax, they directed the outputs of CNN directly to a sequence-to-sequence model. The training data were from Flickr8K, Flickr30K and MSCOCO which were annotated with 5 sentences also using "Amazon Mechanical Turk".

http://cs.stanford.edu/people/karpathy/deepimagesent/
