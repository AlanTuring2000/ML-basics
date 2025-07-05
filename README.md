Complete rewriting - Updated July 2025

# Machine Learning Basics

These notebooks provide correct mathematical proofs and detailed code comments, along with nice figures and illustrations.
Unfortunately, maths is often (I mean always) not presented, or presented poorly in Machine Learning books, and this is what motivated me to write these notebooks in the first place. It seems the most important thing is that the algorithms work, and why they work is secondary to most people. But not to me...

I use and update the highly recommended "Machine Learning with PyTorch and Scikit-Learn" (Jan 2022) by S. Raschka (Packt Publishing). Not only do I follow its development along its 10 first chapters, I also use S. Raschka's choices of datasets and use his excellent codes.
My presentation often goes further than his. As a consequence, I sometimes need to introduce new datasets. Or I use a larger variety of parameters, to test them, or to improve on the book's results.
Of course, the datasets and other external resources used in any notebook are provided as resources within the folder containing the notebook.
As for the codes, I used ChatGPT and/or Deepseek R1 to clarify certain parts; more often ChatGPT because its knowledge is up-to-date or can be updated (since it can go search the internet). Through questions, trials and errors, I was finally able to understand them fully, and I added clear and concise comments for the reader, eg a future me. I believe that anyone with some Python background will be able to understand the code.
I added many code snippets, that I commented as well.
I added a notebook 0 in order for the reader unfamiliar with the pandas and Matplotlib libraries to learn the necessary basics before diving in the main course. For the pandas' library, I reorganized and completed the pandas" part of "Time Series with Deep Learning" by Diogo Alves de Resende ("section 26: Pandas" on Udemy). As for the Matplotlib part, my basis was "section 31: Python intro: Text and plots" of "Master deep learning in PyTorch" (also on Udemy) by Mike X Cohen, that I adapted and completed.

The maths is the difficult part. I have a PhD in maths, and I need correct mathematical proofs to understand and accept any algorithm. I couldn't find these proofs anywhere, so I wrote them myself. I didn't want to write too much, so you need to have good foundations in linear algebra, and a solid understanding of the basics of differentiation in multi-dimensional spaces (up to the Taylor's formulae) as well as of probability theory (up to the law of large numbers).
Again, because I didn't want to write too much, I rewrote much of S. Raschka's explanations, to render them as precisely and concisely as I was able to. Summarizing is my forte, so I believe I succeeded. But my ultimate principle is to prove everything I say, especially when I go further than the book, and sometimes (rarely) this needs thorough discussions.

I wanted my figures to be as beautiful as Machine Learning figures can be. This improves the experience of everyone. So my figures are nicer than those in "the book" (I mean S. Raschka's book). Almost all figures have a title, so the reader can easily know what they illustrate.
Aesthetics is personal, though, and I love cyberpunk colors, I hope you will enjoy them too.
I also improve on the aesthetics of dataframes, by colorizing them. These don't show on Github, unfortunately, you'll need to download the notebooks and run them. And, instead of the usual black output for code results, I colorize them as well. I don't need to tell you which colors' palette I've used in both cases, do I ?

About Machine Learning, I could also have followed the other excellent and famous resource, "Hands-On Machine Learning with Scikit-Learn, Keras & Tensorflow, Third edition" (Oct 2022) by A. Géron (O’Reilly Media).
I quote it, from time to time. I chose Raschka’s book solely because I prefer PyTorch to TensorFlow. They play no role in Machine Learning itself but are pivotal in the next part of my AI-basics course, "DL-basics", where we will learn about Deep Learning.

The original book is very well structured, and S. Raschka masterfully guides us through the intricacies of ML and DL. However, these fields evolve rapidly, making updates necessary.
Some parts of my notebooks will need updating, one day or another. I will rewrite them when needed, as soon as I can.
In the meantime, I hope they enhance your understanding, and that you enjoy reading them!

If you find mistakes or have suggestions, feel free to open an issue! 😊

You can view all notebooks and associated files directly on GitHub, but nbViewer (an official open-source service from Jupyter) offers a slightly better reading experience, as it preserves internal links. To use nbViewer, first copy the URL of the notebook you want to read, then go to
🔗 https://nbviewer.org/
and paste the URL into the input box. You can open multiple notebooks by repeating this process.

Once you find a notebook interesting, you should definitely clone it along with the provided resources. Then, you can use, run, and modify it in Jupyter or SageMaker Studio Lab. This allows you to test various hyperparameter settings and improves your reading experience. However, internal links only work in SageMaker Studio Lab.

One issue with nbViewer is that it limits the number of characters per line, causing some of my longer mathematical expressions to break across multiple lines. Additionally, as in GitHub, my code comments may be cut off, making longer ones unreadable.
Unfortunately, I cannot recommend Google Colab either, as it sometimes renders LaTeX math formulae incorrectly, does not style my notebooks as intended, and also truncates my code comments.

## ⚙️ Running Locally  
To run these notebooks on your computer, install Jupyter Notebook (or JupyterLab) and the following dependencies:

  pip install torch scikit-learn jupyter numpy pandas matplotlib colorama

Other minor dependencies are handled within the notebooks.
Some libraries require manual installation, which I explain directly in the notebooks.