# Generative AI Foundations: MCQs (Generative vs. Discriminative)

1) Which best describes Generative AI?
A. Models that output a single numeric prediction
B. Models that generate new data resembling the training distribution
C. Models that only separate classes with a boundary
D. Models that require labeled data exclusively
Answer: B

2) What do discriminative models primarily learn?
A. The joint distribution p(x, y)
B. The marginal distribution p(x)
C. The conditional distribution p(y | x)
D. The prior p(y)
Answer: C

3) What do generative models commonly learn?
A. Only p(y | x)
B. p(x) or p(x | y)
C. Only decision boundaries between classes
D. Only deterministic mappings from x to y
Answer: B

4) Which is an example of a generative model?
A. Logistic Regression
B. Support Vector Machine (SVM)
C. Variational Autoencoder (VAE)
D. Linear Discriminant Analysis (as a classifier)
Answer: C

5) Which is an example of a discriminative model?
A. Hidden Markov Model (HMM)
B. Gaussian Mixture Model (GMM)
C. Conditional Random Field (CRF)
D. Naive Bayes
Answer: C

6) Which task is most aligned with generative modeling?
A. Spam vs. not-spam classification
B. Image synthesis from text prompts
C. Predicting house prices
D. Classifying sentiment of reviews
Answer: B

7) Which pairing is correct?
A. Generative → p(y | x); Discriminative → p(x)
B. Generative → p(x), p(x | y); Discriminative → p(y | x)
C. Generative → Decision boundary; Discriminative → p(x)
D. Generative → p(y); Discriminative → p(x, y)
Answer: B

8) GANs (Generative Adversarial Networks) are trained using:
A. Mean squared error only
B. A minimax adversarial objective between generator and discriminator
C. K-means clustering objective
D. Purely supervised cross-entropy on labels
Answer: B

9) Autoregressive language models factorize:
A. p(x) = ∏ p(x_t | x_<t)
B. p(y | x) = ∏ p(y_t | x)
C. p(x, y) = p(x) + p(y)
D. p(x) = ∑ p(x_t | y)
Answer: A

10) Diffusion models primarily:
A. Encode inputs to discrete tokens and reconstruct exactly
B. Denoise data by reversing a gradual noising process
C. Learn a single global latent vector per dataset
D. Optimize only classification accuracy
Answer: B

11) A Variational Autoencoder (VAE) typically includes:
A. Only a decoder network
B. An encoder, a decoder, and a KL divergence regularization term
C. A single linear layer plus softmax
D. A k-means objective for clustering
Answer: B

12) Which of the following is a generative sequence model?
A. Hidden Markov Model (HMM)
B. Logistic Regression
C. Conditional Random Field (CRF)
D. Perceptron
Answer: A

13) In the context of generative models, sampling refers to:
A. Computing the maximum a posteriori class
B. Drawing new data points from the learned distribution
C. Minimizing validation error directly
D. Estimating the gradient with respect to labels
Answer: B

14) Mode collapse is a known issue primarily with:
A. VAEs
B. GANs
C. CRFs
D. Linear regression
Answer: B

15) In language models, the temperature parameter in sampling mainly:
A. Increases model accuracy on classification tasks
B. Controls randomness by smoothing or sharpening the output distribution
C. Changes the model architecture
D. Reduces overfitting by adding noise to inputs
Answer: B

16) Which metric is least appropriate for evaluating open-ended text generation quality?
A. ROC-AUC
B. Perplexity
C. BLEU
D. Human evaluation
Answer: A

17) Conditional generation is when a model:
A. Generates data without any input
B. Generates data conditioned on prompts, labels, or other context
C. Only predicts a class label
D. Only reconstructs inputs exactly
Answer: B

18) Discriminative models typically:
A. Learn class-conditional densities p(x | y)
B. Learn priors p(y) explicitly
C. Directly learn decision boundaries between classes
D. Do not require labeled data
Answer: C

19) Which pairing is correct regarding classic models?
A. Naive Bayes → Discriminative; Logistic Regression → Generative
B. Naive Bayes → Generative; Logistic Regression → Discriminative
C. Both are generative
D. Both are discriminative
Answer: B

20) Maximum likelihood training of generative models aims to:
A. Minimize the probability of observed data
B. Maximize p(y | x)
C. Maximize the probability of the observed data under the model
D. Only minimize reconstruction error
Answer: C

21) A common pretraining strategy for generative foundation models is:
A. Fully supervised training with labeled data only
B. Self-supervised learning on large unlabeled corpora
C. Reinforcement learning from the start
D. K-nearest neighbors imputation
Answer: B

22) A unique risk more associated with generative models than discriminative models is:
A. Overfitting on labels
B. Hallucination of plausible but incorrect content
C. Underflow in softmax computations
D. Vanishing gradients in small MLPs
Answer: B

23) Prompt engineering is most relevant to:
A. Discriminative SVM classifiers
B. Generative language models (LLMs)
C. Linear regression with squared loss
D. PCA
Answer: B

24) Unconditional generation refers to:
A. Sampling outputs given inputs
B. Sampling without any conditioning information
C. Predicting y given x labels
D. Classifying with confidence calibration
Answer: B

25) When might you prefer a discriminative model over a generative one?
A. You need to synthesize new high-fidelity images
B. You have abundant labeled data for a classification task and don’t need to generate data
C. You want to simulate the data distribution for anomaly detection
D. You aim to do zero-shot text generation
Answer: B

26) Which statement about p(x, y) is correct?
A. p(x, y) = p(y | x) alone
B. p(x, y) = p(y) only
C. p(x, y) = p(y | x) p(x)
D. p(x, y) = p(x | y)/p(y)
Answer: C

27) Which is a typical advantage of generative models?
A. They inherently require labeled data for training
B. They can generate synthetic samples to augment datasets
C. They cannot model complex distributions
D. They can’t be used for downstream discrimination tasks
Answer: B

28) Which statement best reflects differences in learning signals?
A. Discriminative models can train purely on unlabeled data
B. Generative models can leverage unlabeled data via self-supervision
C. Generative models require densely labeled datasets
D. Discriminative models always require adversarial training
Answer: B

29) In the context of classification, a generative approach typically:
A. Learns p(y | x) and applies Bayes’ rule to get p(x | y)
B. Learns p(x | y) and p(y), then uses Bayes’ rule to compute p(y | x)
C. Ignores p(y)
D. Learns only a separating hyperplane
Answer: B

30) Which risk is especially relevant for large generative models trained on web-scale data?
A. Hyperparameter count always equals dataset size
B. Copyright and data provenance issues in generated outputs
C. They cannot be fine-tuned
D. They cannot overfit
Answer: B
