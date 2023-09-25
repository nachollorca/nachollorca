<h1 align='center'>
  Hola! 👋
</h1>

<p align='center'>
  My friends call me Nacho (yep, like the tortilla chips 🌮) and I am SWE/Data Scientist from Madrid, now based in Berlin. I am using this GitHub to put together some of the projects I can actually showcase, as a (bit untidy) portfolio.
</p>

<p align='center'>
  
  <a href="https://www.linkedin.com/in/illorca/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
  <a href="mailto:madwayesp@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />        
  </a>&nbsp;&nbsp;
  
</p>

<h2>👩&zwj;⚕️ Cross-Corpus NER with Biomedical German Corpora</h2>
<p><img src="https://tinyurl.com/2p9ft7xf" alt="" /> <img src="https://img.shields.io/badge/torch-EE4C2C?style=for-the-badge&amp;logo=pytorch&amp;logoColor=white" alt="" /> <img src="https://img.shields.io/badge/W&amp;B-FFBE00?style=for-the-badge&amp;logo=WeightsAndBiases&amp;logoColor=white" alt="" /></p>
<p>I created harmonized versions of the four clinical, distributable and annotated datasets in German language. Using the harmonized corpora as a meta-dataset, I performed a total of 340 cross-corpus evaluation experiments to assess the generalization capabilities of current-day pre-trained Transformers on each dataset. The paper was worth a <a href="https://aclanthology.org/2023.clinicalnlp-1.23/">publication</a> in the <em>5th Clinical Natural Language Processing Workshop</em> of the ACL. An extended version of the work with a substantially larger k-fold experimental design will come out shortly. The datasets can be applied for through their respective DUAs. Unfortunately, the code and model checkpoints are kept private due to GDPR concerns.</p>

<h2>📱<a href="https://github.com/hpi-dhc/xmen">CLI and PiPy for a Cross-lingual Medical Entity Linking Toolkit</a></h2>
<p><img src="https://img.shields.io/badge/pypi-3775A9?style=for-the-badge&amp;logo=pypi&amp;logoColor=white" alt="" /> <img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&amp;logo=gnu-bash&amp;logoColor=white" alt="" /></p>
<p>I participated in the development of <em>xMEN</em>, a python package for cross-lingual (x) Medical Entity Normalization. Mainly, I took care of the <a href="https://pypi.org/project/xmen/">pypi integration</a>, the <a href="https://github.com/hpi-dhc/xmen/tree/main/xmen/cli">Command Line Interface</a>, unit tests and documentation. We used the application for the first time to obtain SOTA results in the <em>Disease Text Mining Shared Task</em> from the Barcelona Supercomputing Center. We presented the results in <a href="https://link.springer.com/chapter/10.1007/978-3-031-42448-9_12">this book</a> for the <em>International Conference of the Cross-Language Evaluation Forum for European Languages 2023</em>. The content is blocked after a paywall, just ping me if you'd like to read a copy of our paper.</p>

<h2>🔍 <a href="https://huggingface.co/spaces/hpi-dhc/FairEval/tree/main">Novel NLP Evaluation Module Implementation for HuggingFace</a></h2>
<p><img src="https://tinyurl.com/2p9ft7xf" alt="" /> <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&amp;logo=python&amp;logoColor=blue" alt="" /></p>
<p><a href="https://aclanthology.org/2022.lrec-1.150">Katrin Ortmann presented in 2022</a> a new evaluation method that more accurately reflects true prediction quality for labeled span-based metrics. We thought the idea was fantastic, so I provided an implementation within the HuggingFace Evaluate module to democratize its use. It has already been of help in some workshops and shared tasks. Just follow the link to see the code!</p>

<h2>🕵️ Multi-modal Face Anti Spoofing</h2>
<p><img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&amp;logo=numpy&amp;logoColor=white" alt="" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&amp;logo=pytorch&amp;logoColor=white" alt="" />&nbsp;<img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&amp;logo=OpenCV&amp;logoColor=white" alt="" /></p>
<p>I developed an application to detect whether the face in front of the camera is real or fake (a print, a screen...) for a Kiosk manufacturing company. I use a CNN trained separately on RGB, infrared and depth information and test its performance on a self-recorded dataset, paying special attention to the effects of different conditions of room lighting or camera position. The depth model proves to be superior in most scenarios, notably obtaining 0.05 ACER score across all settings. A <a href="https://drive.google.com/file/d/1d7eMCKSXbZ7GW82jbXNbqPdGC_p_TZWj/view?usp=sharing">summary of the project development can be read here</a>. The code unfortunately belongs to the company and cannot be shown.</p>

<h2>🎻 <a href="https://musicator.streamlit.app">Music Genre Classification</a></h2>
<p><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&amp;logo=Streamlit&amp;logoColor=white" alt="" /> <img src="https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&amp;logo=keras&amp;logoColor=white" alt="" /> <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&amp;logo=pandas&amp;logoColor=white" alt="" /></p>
<p>Musicator is my OOP-Python program with Streamlit frontend that uses a neural network trained on the GTZAN dataset to guess the genre of a song among blues, classical, country, disco, hiphop, jazz, metal, pop, reggae and rock. The source code and and Jupyter Notebook with an extensive analysis of the problem can be seen <a href="https://github.com/nachollorca/musicator">on this repo</a>.</p>

<h2>🟢 Open Source Contributions</h2>
<p><img src="https://tinyurl.com/2p9ft7xf" alt="" /> <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="" /></p>
<p>I am always on the look to do my bit for open-source efforts that I use frequently. As such, I am a top contributor for <a href="https://github.com/bigscience-workshop/biomedical/graphs/contributors">BigBIO</a>, I made some improvements in <a href="https://github.com/allenai/scispacy/pull/478">Sci-spaCy</a>) or included various modules and models in <a href="https://huggingface.co/hpi-dhc">Hugging Face</a>.</p>

<h2>😐 <a href="https://github.com/nachollorca/facial-landmark-detection/">Facial Landmark Detection</a></h2>
<p><img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&amp;logo=OpenCV&amp;logoColor=white" alt="" /> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&amp;style=for-the-badge&amp;logo=Jupyter&amp;logoColor=white" alt="" /></p>
<p>Old computer-vision application I developed with a couple of classmates on the use of CNNs to detect facial landmarks (points that define mouth, eyes, nose, eyebrows, etc.) for face recognition.</p>

## ➗ Mathematical Foundations of ML Algorithms 
My M. Sc. was very heavy on statistics. I have compiled some interesting implementations I did from scratch of various Machine Learning methods in jupyter notebooks. 
[🚧 under construction 🚧]

## Others 
Some other smaller or shared projects. [🚧 under construction 🚧]
- 🦠 __Epidemiological Data Analysis in R-language__: I had access to a sweet German biomedical dataset, so here is a varied statistical analysis I performed to show my R skills.
- 💲 __Impact of Paid Subscriptions in Physician Platforms__: in 2020, I conducted an investigation with a couple classmates about whether paying a subscription has a significant effect on the ratings of medical physicians in the platform [Jameda](https://www.jameda.de/). 
- 🗃️ __ETL tools for Master Data Management__: brief literature survey of ETL and MDM with a fictional demonstration of some use cases.
