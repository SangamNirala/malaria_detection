<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Malaria Detection Using Deep Learning</title>
</head>
<body>
    <h1>Malaria Detection Using Deep Learning</h1>

    <h2>Overview</h2>
    <p>
        This project implements a deep learning model for detecting malaria in blood cell images using TensorFlow. The model leverages various architectures, including CNNs and transfer learning techniques, to classify images as infected or uninfected.
    </p>

    <h2>Features</h2>
    <ul>
        <li>Data augmentation and preprocessing techniques to enhance model performance.</li>
        <li>Utilizes TensorFlow Datasets for loading the malaria dataset.</li>
        <li>Implements model training, evaluation, and visualization of results.</li>
        <li>Supports model versioning and logging with Weights & Biases (WandB).</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/yourusername/malaria-detection.git
cd malaria-detection</code></pre>
        </li>
        <li>Install the required packages:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
    </ol>

    <h2>Usage</h2>
    <ol>
        <li>Prepare your dataset in the specified directory structure.</li>
        <li>Run the training script:
            <pre><code>python train.py</code></pre>
        </li>
        <li>Evaluate the model:
            <pre><code>python evaluate.py</code></pre>
        </li>
    </ol>

    <h2>Results</h2>
    <p>
        The model achieves high accuracy in classifying malaria-infected and uninfected images. Visualizations of the training process and performance metrics are included in the results directory.
    </p>

    <h2>License</h2>
    <p>
        This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.
    </p>
</body>
</html>
