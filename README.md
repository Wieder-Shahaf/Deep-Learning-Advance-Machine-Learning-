<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Deep Learning Techniques and Model Evaluation</h1>

<h2>Overview</h2>
<p>This repository covers deep learning concepts such as Convolutional Neural Networks, Generative Adversarial Networks, Recurrent Neural Networks, Adversarial Attacks, and Contrastive Learning. Each exercise demonstrates practical implementation, optimization techniques, and model evaluation strategies:</p>

<ol>
    <li><strong>Convolutional Neural Networks (CNNs):</strong> Implementing and training CNNs for image classification.</li>
    <li><strong>Fully Connected Networks and Recurrent Neural Networks (RNNs):</strong> Addressing tasks of overfitting, sentiment analysis, and sequence modeling.</li>
    <li><strong>Generative Adversarial Networks (GANs):</strong> Building and training GANs for image generation.</li>
    <li><strong>Adversarial Attacks and Adversarial Training:</strong> Implementing FGSM attacks on CNNs and enhancing model robustness through adversarial training.</li>
    <li><strong>Contrastive Learning:</strong> Exploring unsupervised representation learning through contrastive methods and data augmentation.</li>
</ol>

<h2>Convolutional Neural Networks (Exercise 1)</h2>
<p>In this exercise, we implemented and trained a CNN model with depthwise separable convolutions:</p>
<ul>
    <li>Designed a CNN architecture for image classification.</li>
    <li>Used depthwise and pointwise convolutional layers to reduce model parameters.</li>
    <li>Evaluated performance with adaptive pooling and fully connected layers.</li>
</ul>
<p><strong>Challenge:</strong> Balancing model size, complexity, and accuracy while preventing overfitting.</p>

<h2>Fully Connected Networks and RNNs (Exercise 2)</h2>
<p>This exercise demonstrated:</p>
<ul>
    <li>Overfitting phenomena by training fully connected networks on random-labeled MNIST samples.</li>
    <li>Implementing Vanilla RNN and GRU models for sentiment classification of tweets into emotions (happiness, sadness, neutral).</li>
    <li>Applying tokenization, vocabulary creation, and sequence padding for text processing.</li>
</ul>
<p><strong>Challenge:</strong> Mitigating overfitting and optimizing hyperparameters (e.g., embedding size, hidden units, dropout rates) for better generalization.</p>

<h2>Generative Adversarial Networks (Exercise 3)</h2>
<p>This exercise included training DCGAN on the Tiny-ImageNet dataset:</p>
<ul>
    <li>Implemented Generator and Discriminator architectures following DCGAN principles.</li>
    <li>Optimized GAN training stability using Adam optimizer and BCEWithLogitsLoss.</li>
    <li>Generated sample images and evaluated quality visually.</li>
</ul>
<p><strong>Challenge:</strong> Ensuring GAN stability, addressing mode collapse, and tuning latent space dimensionality.</p>

<h2>Adversarial Attacks and Training on SVHN (Exercise 4)</h2>
<p>This exercise involved evaluating CNN robustness:</p>
<ul>
    <li>Trained CNN to achieve ~94% accuracy on the SVHN digit dataset.</li>
    <li>Implemented Fast Gradient Sign Method (FGSM) adversarial attacks with varying epsilon values.</li>
    <li>Analyzed visual and performance impacts of adversarial perturbations.</li>
    <li>Performed adversarial training to enhance model robustness, maintaining 70%+ accuracy against FGSM attacks at ε=0.1.</li>
</ul>
<p><strong>Challenge:</strong> Balancing robustness against adversarial attacks and maintaining high accuracy on clean data.</p>

<h2>Contrastive Learning (Exercise 5)</h2>
<p>This theoretical exercise examined unsupervised representation learning:</p>

<h3>Core Concepts</h3>
<ul>
    <li>Explained the importance of large batch sizes for effective contrastive learning.</li>
    <li>Evaluated unsupervised embeddings via linear probing and clustering metrics.</li>
    <li>Discussed suitable data augmentation techniques for contrastive methods, including random cropping, rotations, Gaussian noise, and grayscale transformations.</li>
</ul>

<h3>Analysis and Results</h3>
<ul>
    <li>Investigated semantic coherence of learned embeddings via nearest-neighbor analysis.</li>
    <li>Identified limitations in current embeddings, such as incorrect semantic grouping.</li>
    <li>Proposed improvements in training data quality and refining contrastive loss function.</li>
</ul>

<h2>Conclusion</h2>
<p>This repository demonstrates deep learning methodologies including CNNs, GANs, RNNs, adversarial attacks, and contrastive learning. Each exercise provides insights into model design, optimization strategies, robustness considerations, and representation learning.</p>

</body>
</html>
