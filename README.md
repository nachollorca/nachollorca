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
  <a href="mailto:nacho_llorca@outlook.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />        
  </a>&nbsp;&nbsp;
  
</p>

### 👩‍⚕️ Cross-corpus NER with German Biomedical Corpora <img align="right" src="https://tinyurl.com/2p9ft7xf"/> <img align="right" src="https://img.shields.io/badge/torch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> <img align="right" src="https://img.shields.io/badge/W&B-FFBE00?style=for-the-badge&logo=WeightsAndBiases&logoColor=white" />
I created harmonized versions of the four clinical, distributable and annotated datasets in German language. Using the harmonized corpora as a meta-dataset, I performed a total of 340 cross-corpus evaluation experiments to assess the generalization capabilities of current-day pre-trained Transformers on each dataset. The paper was worth a [publication](https://aclanthology.org/2023.clinicalnlp-1.23/) in the _5th Clinical Natural Language Processing Workshop_ of the ACL. An extended version of the work with a substantially larger k-fold experimental design will come out shortly. 

The datasets can be applied for through their respective DUAs. Unfortunately, the code and model checkpoints are kept private due to GDPR concerns. 

### [📱CLI and PiPy for a Cross-lingual Medical Entity Linking Toolkit](https://github.com/hpi-dhc/xmen) <img align="right" src="https://img.shields.io/badge/pypi-3775A9?style=for-the-badge&logo=pypi&logoColor=white" /> <img align="right" src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
I participated in the development of __xMEN__, a python package for cross-lingual (x) Medical Entity Normalization. Mainly, I took care of the [pypi integration](https://pypi.org/project/xmen/), the [Command Line Interface](https://github.com/hpi-dhc/xmen/tree/main/xmen/cli), unit tests and documentation. We used the application for the first time to obtain SOTA results in the _Disease Text Mining Shared Task_ from the Barcelona Supercomputing Center. We presented the results in [this book](https://link.springer.com/chapter/10.1007/978-3-031-42448-9_12#citeas) for the _International Conference of the Cross-Language Evaluation Forum for European Languages 2023_. The content is blocked after a paywall, just ping me if you'd like to read a copy of our paper.

### [🔍 Novel NLP Evaluation Module Implementation for HuggingFace](https://huggingface.co/spaces/hpi-dhc/FairEval/tree/main) <img align="right" src="https://tinyurl.com/2p9ft7xf"/> <img align="right" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
[Katrin Ortmann presented in 2022](https://aclanthology.org/2022.lrec-1.150) a new evaluation method that more accurately reflects true prediction quality for labeled span-based metrics. We thought the idea was fantastic, so I provided an implementation within the HuggingFace Evaluate module to democratize its use. It has already been of help in some workshops and shared tasks as []. Just follow the link to see the code!
 
### 🕵️ Multi-modal Face Anti Spoofing <img align="right" src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white" /> <img align="right" src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" /> <img align="right" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
I developed an application to detect whether the face in front of the camera is real or fake (a print, a screen...) for a Kiosk manufacturing company. I use a CNN trained separately on RGB, infrared and depth information and test its performance on a self-recorded dataset, paying special attention to the effects of different conditions of room lighting or camera position. The depth model proves to be superior in most scenarios, notably obtaining 0.05 ACER score across all settings. A summary of the project development can be read [here](https://drive.google.com/file/d/1d7eMCKSXbZ7GW82jbXNbqPdGC_p_TZWj/view?usp=sharing). The code unfortunately belongs to the company.

### 🎻 [Music Genre Classification](https://github.com/nachollorca/musicator) <img align="right" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" /> <img align="right" src="https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white" /> <img align="right" src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />
A fun little project where I attempt to classify songs within 10 music genres discussing different methods, from random forests to simple neural networks. 

### 🟢 Open Source Contributions <img align="right" src="https://tinyurl.com/2p9ft7xf"/> <img align="right" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
I am always on the look to doing my bit for open-source efforts that I use frequently. As such, I am a top contributor for [BigBIO](https://github.com/bigscience-workshop/biomedical/graphs/contributors), I made some improvements in [Sci spaCy](https://github.com/allenai/scispacy/pull/478) or included various modules and models in [Hugging Face](https://huggingface.co/hpi-dhc).

### 😐 [Facial Landmark Detection](https://github.com/nachollorca/facial-landmark-detection/) <img align="right" src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white" /> <img align="right" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" />
Old computer-vision application I developed with a couple of classmates on the use of CNNs to detect facial landmarks (points that define mouth, eyes, nose, eyebrows, etc.) for face recognition.

### ➗ Mathematical Foundations of ML Algorithms 
My M. Sc. was very heavy on statistics. I have compiled some interesting implementations I did from scratch of various Machine Learning methods in jupyter notebooks. 
[🚧 under construction 🚧]

### Others 
Some other smaller or shared projects. [🚧 under construction 🚧]
- 🦠 __Epidemiological Data Analysis in R-language__: I had access to a sweet German biomedical dataset, so here is a varied statistical analysis I performed to show my R skills.
- 💲 __Impact of Paid Subscriptions in Physician Platforms__: in 2020, I conducted an investigation with a couple classmates about whether paying a subscription has a significant effect on the ratings of medical physicians in the platform [Jameda](https://www.jameda.de/). 
- 🗃️ __ETL tools for Master Data Management__: brief literature survey of ETL and MDM with a fictional demonstration of some use cases.
