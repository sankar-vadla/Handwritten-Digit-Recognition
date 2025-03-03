# Handwritten-Digit-Recognition
Neural network based project with MNIST dataset.
<br>
Integrated GUI created for recognition of written digits on screen.
<br>
Built using a three-layered neural network(input, hidden, and output layers).
<br>
<h2>Overview</h2>
<ul>
  <li>Imported required libraries(Numpy, Scipy, TKinter) and data extracted from the mnist-original.mat file.</li>
  <li>Separated features and labels from the extracted data.</li>
  <li>Data splitted into training set(60,000 examples) and testing set(10,000 examples).</li>
  <li>Randomly initiated thetas within the range [-0.15,+0.15] to break symmetry and improve training results.</li>
  <li>"minimize" optimizer from the scipy.optimize library is used with the "L-BFGS-B" method for training.</li>
  <li>Performed feed-forward propagation to process input data through hidden layers using the sigmoid activation function.</li>
  <li>Performed backpropagation to fine-tune weights based on the error rate from previous iterations.</li>
  <li>Calculated cross-entropy costs to measure the error between predictions and original values.</li>
  <li>Computed gradients to optimize weights and minimize the cost function.</li>
  <li>Performed forward propagation to predict the handwritten digit.</li>
  <li>Implemented a GUI to allow writing digits, convert them to grayscale, resize to (28 x 28) pixels, and store the image for digit recognition.</li>
</ul>
