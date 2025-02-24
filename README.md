# Machine Learning Basics

In these notebooks, I update the older parts of the highly recommended "Machine Learning with PyTorch and Scikit-Learn" (Jan 2022) by S. Raschka (Packt Publishing). I provide correct and complete mathematical proofs, detailed code comments, additional information and code snippets, more meaningful examples where useful, and I rewrite most explanations.

About Machine Learning, I could also have followed the other excellent and famous resource, "Hands-On Machine Learning with Scikit-Learn, Keras & Tensorflow, Third edition" (Oct 2022) by A. Géron (O’Reilly Media).
I quote it, from time to time. I chose Raschka’s book solely because I prefer PyTorch to TensorFlow. They play no role in Machine Learning itself but are pivotal in the next part of my AI-basics course, "DL-basics", where we will learn about Deep Learning.

I have a PhD in math, and I used my expertise to provide correct proofs where S. Raschka fell short - which, unfortunately, is almost everywhere he discusses mathematics 😉.

At last, the code was difficult for me, and I questioned ChatGPT and/or Deepseek R1 extensively to get concise and clear line by line explanations.

The original book is very well structured, and S. Raschka masterfully guides us through the intricacies of ML and DL. However, these fields evolve rapidly, making updates necessary.

Some parts of my notebooks will need updating, one day or another. I will rewrite them when needed, as soon as I can.
In the meantime, I hope they enhance your understanding, and that you enjoy reading them!

If you find mistakes or have suggestions, feel free to open an issue! 😊

You can view all notebooks and associated files directly on GitHub, but nbViewer (an official open-source service from Jupyter) offers a slightly better reading experience, as it preserves internal links. To use nbViewer, copy the URL of the notebook you want to read, go to
🔗 https://nbviewer.org/
and paste the URL into the input box. You can open multiple notebooks by repeating this process.

Once you find my notebook interesting, you should definitely clone it along with the provided resources. Then, you can use, run, and modify it in Jupyter or SageMaker Studio Lab. This allows you to test various hyperparameter settings and improves your reading experience. However, internal links only work in SageMaker Studio Lab.

One issue with nbViewer is that it limits the number of characters per line, causing some of my longer mathematical expressions to break across multiple lines. Additionally, as in GitHub, my code comments may be cut off, making longer ones unreadable.

Unfortunately, I cannot recommend Google Colab, as it sometimes renders LaTeX math formulae incorrectly, does not style my notebooks as intended, and also truncates my code comments.

## ⚙️ Running Locally  
To run these notebooks on your computer, install Jupyter Notebook (or JupyterLab) and the following dependencies:

  pip install torch scikit-learn jupyter numpy pandas matplotlib colorama

Other minor dependencies are handled within the notebooks.
Some libraries require manual installation, which I explain directly in the notebooks.