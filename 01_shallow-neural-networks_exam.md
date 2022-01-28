<meta charset="utf-8"/>
<h3>
 Question 1
</h3>
<co-content>
 <p>
  Which of the following are true? (Check all that apply.)
 </p>
</co-content>
<form>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$a^{[2](12)}$$ denotes the activation vector of the $$2^{nd}$$ layer for the $$12^{th}$$ training example.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$a^{[2](12)}$$ denotes activation vector of the $$12^{th}$$ layer on the $$2^{nd}$$ training example.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$X$$ is a matrix in which each column is one training example.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$a^{[2]}_4$$ is the activation output by the $$4^{th}$$ neuron of the $$2^{nd}$$ layer
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$a^{[2]}$$ denotes the activation vector of the $$2^{nd}$$ layer.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$X$$ is a matrix in which each row is one training example.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="0" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$a^{[2]}_4$$ is the activation output of the $$2^{nd}$$ layer for the $$4^{th}$$ training example
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 2
</h3>
<co-content>
 <p>
  The tanh activation is not always better than sigmoid activation function for hidden units because the mean of its output is closer to zero, and so it centers the data, making learning complex for the next layer. True/False?
 </p>
</co-content>
<form>
 <label>
  <input name="1" type="radio"/>
  <co-content>
   <span>
    False
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="1" type="radio"/>
  <co-content>
   <span>
    True
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 3
</h3>
<co-content>
 <p hasmath="true">
  Which of these is a correct vectorized implementation of forward propagation for layer $$l$$, where $$1 \leq l \leq L$$?
 </p>
</co-content>
<form>
 <label>
  <input name="2" type="radio"/>
  <co-content>
   <ul bullettype="bullets">
    <li>
     <span hasmath="true">
      $$Z^{[l]} = W^{[l]} A^{[l]}  b^{[l]}$$
     </span>
    </li>
    <li>
     <span hasmath="true">
      $$A^{[l 1]} = g^{[l]}(Z^{[l]})$$
     </span>
    </li>
   </ul>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="2" type="radio"/>
  <co-content>
   <ul bullettype="bullets">
    <li>
     <span hasmath="true">
      $$Z^{[l]} = W^{[l-1]} A^{[l]}  b^{[l-1]}$$
     </span>
    </li>
    <li>
     <span hasmath="true">
      $$A^{[l]} = g^{[l]}(Z^{[l]})$$
     </span>
    </li>
   </ul>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="2" type="radio"/>
  <co-content>
   <ul bullettype="bullets">
    <li>
     <span hasmath="true">
      $$Z^{[l]} = W^{[l]} A^{[l]}  b^{[l]}$$
     </span>
    </li>
    <li>
     <span hasmath="true">
      $$A^{[l 1]} = g^{[l 1]}(Z^{[l]})$$
     </span>
    </li>
   </ul>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="2" type="radio"/>
  <co-content>
   <ul bullettype="bullets">
    <li>
     <span hasmath="true">
      $$Z^{[l]} = W^{[l]} A^{[l-1]}  b^{[l]}$$
     </span>
    </li>
    <li>
     <span hasmath="true">
      $$A^{[l]} = g^{[l]}(Z^{[l]})$$
     </span>
    </li>
   </ul>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 4
</h3>
<co-content>
 <p>
  You are building a binary classifier for recognizing cucumbers (y=1) vs. watermelons (y=0). Which one of these activation functions would you recommend using for the output layer?
 </p>
</co-content>
<form>
 <label>
  <input name="3" type="radio"/>
  <co-content>
   <span>
    ReLU
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="3" type="radio"/>
  <co-content>
   <span>
    tanh
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="3" type="radio"/>
  <co-content>
   <span>
    Leaky ReLU
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="3" type="radio"/>
  <co-content>
   <span>
    sigmoid
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 5
</h3>
<co-content>
 <p>
  Consider the following code:
 </p>
 <p>
  A = np.random.randn(4,3)B = np.sum(A, axis = 1, keepdims = True)
 </p>
 <p>
  What will be B.shape? (If you’re not sure, feel free to run this in python to find out).
 </p>
</co-content>
<form>
 <label>
  <input name="4" type="radio"/>
  <co-content>
   <span>
    (1, 3)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="4" type="radio"/>
  <co-content>
   <span>
    (, 3)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="4" type="radio"/>
  <co-content>
   <span>
    (4, 1)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="4" type="radio"/>
  <co-content>
   <span>
    (4, )
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 6
</h3>
<co-content>
 <p>
  Suppose you have built a neural network. You decide to initialize the weights and biases to be zero. Which of the following statements is true?
 </p>
</co-content>
<form>
 <label>
  <input name="5" type="radio"/>
  <co-content>
   <span>
    Each neuron in the first hidden layer will perform the same computation. So even after multiple iterations of gradient descent each neuron in the layer will be computing the same thing as other neurons.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="5" type="radio"/>
  <co-content>
   <span>
    Each neuron in the first hidden layer will compute the same thing, but neurons in different layers will compute different things, thus we have accomplished “symmetry breaking” as described in lecture.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="5" type="radio"/>
  <co-content>
   <span>
    Each neuron in the first hidden layer will perform the same computation in the first iteration. But after one iteration of gradient descent they will learn to compute different things because we have “broken symmetry”.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="5" type="radio"/>
  <co-content>
   <span>
    The first hidden layer’s neurons will perform different computations from each other even in the first iteration; their parameters will thus keep evolving in their own way.
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 7
</h3>
<co-content>
 <p>
  Logistic regression’s weights w should be initialized randomly rather than to all zeros, because if you initialize to all zeros, then logistic regression will fail to learn a useful decision boundary because it will fail to “break symmetry”, True/False?
 </p>
</co-content>
<form>
 <label>
  <input name="6" type="radio"/>
  <co-content>
   <span>
    True
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="6" type="radio"/>
  <co-content>
   <span>
    False
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 8
</h3>
<co-content>
 <p>
  You have built a network using the tanh activation for all the hidden units. You initialize the weights to relative large values, using np.random.randn(..,..)*1000. What will happen?
 </p>
</co-content>
<form>
 <label>
  <input name="7" type="radio"/>
  <co-content>
   <span>
    This will cause the inputs of the tanh to also be very large, thus causing gradients to be close to zero. The optimization algorithm will thus become slow.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="7" type="radio"/>
  <co-content>
   <span>
    This will cause the inputs of the tanh to also be very large, causing the units to be “highly activated” and thus speed up learning compared to if the weights had to start from small values.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="7" type="radio"/>
  <co-content>
   <span>
    It doesn’t matter. So long as you initialize the weights randomly gradient descent is not affected by whether the weights are large or small.
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="7" type="radio"/>
  <co-content>
   <span hasmath="true">
    This will cause the inputs of the tanh to also be very large, thus causing gradients to also become large. You therefore have to set $$\alpha$$ to be very small to prevent divergence; this will slow down learning.
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 9
</h3>
<co-content>
 <p>
  Consider the following 1 hidden layer neural network:
 </p>
 <img assetid="su0xowjlQROtMaMI5YETYA" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASwAAADhCAYAAAByfIirAABHeUlEQVR42u2dd5Ac9bXv9ccrv1v2fcWtsl1lv3svplwGGy7YRF9sjHkEE4RERmQjoggSwSDA5CyBCCL4gi2CTLIECCTACCGUpZVWq7RRcXeVVjmiHHZ+bz5n9tf7656e0LOzszO751DDaGd6enpm+vftE77ne7oZtYJaLBYzzc3N3o2/27KdmlpXsm76FRTGLPAEbfee3Wbr1q1mzZo1ZtWqVWb9+vVmx44dZv/+/aH7UOBSU8BSa3ePytrevXtNfX29+eLzL8yzzz5r7vzTnea2224z11xzjbnqqqtMnz59zB133GHuvfde8+abb5rp06ebjRs3JgGXmpoCllrevSprmzdvNt+M/cbcdNNNpmfPngJKr776qvn888/NzJkzzbx580xlZaWZO3eumTRpknn//ffNE088Ya6++mpz2mmnmZdfftksWrTI87zU21JTwFLLu1e1Z88eM2bMGHP++eebCy+80HzyySdmyZIlZteuXVnta8OGDaZ8ZrkZNGiQOeigg8wzzzxjGhsb1dtSU8BSyw9YWc9n+fLl5s9//rM54YQTzNdjvzbffvutf9tmf2I9eHM9KP7d0NAggPXDH/5QPLN9+/YpaKkpYKnlDlbWKioqzPe++z3z/PPPi5fkekQWjDKFdHab5v3NvsfKy8tN9+7dzVNPPyUJewUtNQUstZzBavLkyaZbt25m5MiR3uOpqoRRw0y7v7Vr15qbb77Z9O7d20vKK2ipKWCpZQaT+H/NsQRYlJWVCVhNmTLF51VlG0oGvS7f37HEvmwouG3bNtO/f39z/fXXq6elpoCllp3tb05U7ubPny9g9fXXX0fyqlIBFTku+3gwn2WrhYAWVAhyW/YxrR6qKWCphZoFJDycK664QrhTqUAo0362b98u+3FBzgU9KotbtmyRyqMLWpBOTznlFDN69Gj1stQUsNQye0ZvDx0qno6lK0TxrACejz/+2Lzyyitm9uzZAki7d+8248ePFz6W3efKlSvNqFGjzMCBA+XfmA0PCUX/5X//i1mxYoWClpoCllpq72rZsmXmpz/7mRA/o4CFBSxAp2/fvubvf/+793qIpnCvLrroIg+w2HbdunXC56qpqUmEoy1eFvdPP/20VCXDwkg1NQWsLu5dWYOF/uSTT3pA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"/>
 <p>
  Which of the following statements are True? (Check all that apply).
 </p>
</co-content>
<form>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$b^{[2]}$$ will have shape (4, 1)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$b^{[1]}$$ will have shape (2, 1)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$b^{[1]}$$ will have shape (4, 1)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$b^{[2]}$$ will have shape (1, 1)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$W^{[2]}$$ will have shape (1, 4)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$W^{[1]}$$ will have shape (2, 4)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$W^{[1]}$$ will have shape (4, 2)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="8" type="checkbox"/>
  <co-content>
   <span hasmath="true">
    $$W^{[2]}$$ will have shape (4, 1)
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<h3>
 Question 10
</h3>
<co-content>
 <p hasmath="true">
  In the same network as the previous question, what are the dimensions of $$Z^{[1]}$$ and $$A^{[1]}$$?
 </p>
</co-content>
<form>
 <label>
  <input name="9" type="radio"/>
  <co-content>
   <span hasmath="true">
    $$Z^{[1]}$$ and $$A^{[1]}$$ are (4,1)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="9" type="radio"/>
  <co-content>
   <span hasmath="true">
    $$Z^{[1]}$$ and $$A^{[1]}$$ are (4,m)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="9" type="radio"/>
  <co-content>
   <span hasmath="true">
    $$Z^{[1]}$$ and $$A^{[1]}$$ are (4,2)
   </span>
  </co-content>
  <br/>
 </label>
 <label>
  <input name="9" type="radio"/>
  <co-content>
   <span hasmath="true">
    $$Z^{[1]}$$ and $$A^{[1]}$$ are (1,4)
   </span>
  </co-content>
  <br/>
 </label>
</form>
<hr/>
<style>
 body {
    padding: 50px 85px 50px 85px;
}

table th, table td {
    border: 1px solid #e0e0e0;
    padding: 5px 20px;
    text-align: left;
}
input {
    margin: 10px;
}
}
th {
    font-weight: bold;
}
td, th {
    display: table-cell;
    vertical-align: inherit;
}
img {
    height: auto;
    max-width: 100%;
}
pre {
    display: block;
    margin: 20px;
    background: #424242;
    color: #fff;
    font-size: 13px;
    white-space: pre-wrap;
    padding: 9.5px;
    margin: 0 0 10px;
    border: 1px solid #ccc;
}
</style>
<script async="" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript">
</script>
<script type="text/x-mathjax-config">
 MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$$','$$'], ['$','$'] ],
      displayMath: [ ["\\[","\\]"] ],
      processEscapes: true
    }
  });
</script>
