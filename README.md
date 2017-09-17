# homework0
Please write about a deep learning expert in your README.md.
he/she can be a professor (e.g., Yann LeCun), a Ph.D student (e.g., Joseph Chet Redmon), a hacker (e.g., Flood Sung), a researcher (e.g., John Schulman), an enginner (e.g., Soumith Chintala), an entrepreneur (e.g., Matthew Zeiler), etc.
To avoid writing the same person, please report the person's name in  
https://docs.google.com/spreadsheets/d/153XruMO7DPONzBTkxh8ZoYSto1E_2zO021vs0prWZ_Q/edit?usp=sharing
First come first serve!

---

# Diederik P. Kingma

[Diederik P. Kingma](http://dpkingma.com) is currently a Machine Learning researcher at [OpenAI](www.openai.com). He received his MS degree in Informatics from Utrecht University and his final thesis was done with [Yann LeCun](http://yann.lecun.com) at NYU. In addition to being a ML researcher, he's also purchasing his PhD degree at Univ. of Amsterdam.

He's known for his contribution in [variational encoder (VAE)](https://arxiv.org/abs/1312.6114) and the [Adam optimizer](https://arxiv.org/abs/1412.6980).

VAE is definitely a classic generative model in this deep learning wave. By constraining the encoder to output a latent variable with Gaussian distribution by appeending a Kullback–Leibler divergence term to the loss. This helps the encoder embedding more information and improves the generated results a lot.

Adam optimizer, it's probably the most commonly used optimizer these years. In the paper, Adam is described as follow.
>The method is straightforward to implement, is computationally efficient, has little memory requirements, is invariant to diagonal rescaling of the gradients, and is well suited for problems that are large in terms of data and/or parameters. The method is also appropriate for non-stationary objectives and problems with very noisy and/or sparse gradients. The hyper-parameters have intuitive interpretations and typically require little tuning.

And empirically, it is proved to work better in most situations.

In addition to VAE and Adam mentioned above, Kingma sure has other brilliant works, you can visit his [website](http://dpkingma.com) for more.