# MSc Project

Paper and code for my MSc Project at the University of Bristol (2021): 'Evaluating Combined Fairness Metrics in GANs'.

<b>Abstract:</b>

Bias in algorithmic decision-making can perpetuate and even exacerbate discrimination against disadvantaged subgroups of the population. Discrimination is also deeply embedded into the data we use to train algorithms. Various techniques have historically been employed to make this data and the models that use it more fair.

However, fairness itself is a complicated and contested topic. This work will explore the many ways in which fairness can be measured and demonstrate the theoretical impossibility of guaranteeing 'total' fairness in a binary classifier.

Next, drawing on adversarial training to generate debiased synthetic data, we combine two popular fairness metrics in the loss function of a GAN and generate synthetic datasets that show an overall improvement in these two metrics when used to train a binary classifier. The model can be weighted towards one metric or the other by changing the parameterisation of the loss function.

Finally, we will discuss the resulting fairness-accuracy trade-off and explore situations in which combined fairness might be helpful.

The main contributions of this project are:
<br> • The first known GAN designed to make a trade-off between two fairness metrics
<br> • An examination of how changing the weighting of this trade-off affects fairness
<br> • A significant result that will aid multi-stakeholder decision-making where trade-offs between different fairness metrics are necessary
