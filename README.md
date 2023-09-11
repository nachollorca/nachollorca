## Hola! 👋
My friends call me Nacho (yep, like the tortilla chips 🌮) and I am Data Scientist from Madrid, now based in Berlin. I am using this GitHub to put together some of the projects I can actually showcase, as a (bit untidy) portfolio. 

To see my CV just check [LinkedIn](https://www.linkedin.com/in/illorca/). Feel free to [write me](mailto:nacho_llorca@outlook.com) with any inquiry!

### 👩‍⚕️ Cross-corpus NER with German Biomedical Corpora
I created harmonized versions of the four clinical, distributable and annotated datasets in German language. Using the harmonized corpora as a meta-dataset, I performed a total of 340 cross-corpus evaluation experiments to assess the generalization capabilities of current-day pre-trained Transformers on each dataset. The paper was worth a [publication](https://aclanthology.org/2023.clinicalnlp-1.23/) in the _5th Clinical Natural Language Processing Workshop_ of the ACL. An extended version of the work with a substantially larger k-fold experimental design will come out shortly. 

The datasets can be applied for through their respective DUAs. Unfortunately, the code and model checkpoints are kept private due to GDPR concerns. 

### [📱CLI and PiPy for a Cross-lingual Medical Entity Linking Toolkit](https://github.com/hpi-dhc/xmen)
I participated in the development of __xMEN__, a python package for cross-lingual (x) Medical Entity Normalization. Mainly, I took care of the [pypi integration](https://pypi.org/project/xmen/), the [Command Line Interface](https://github.com/hpi-dhc/xmen/tree/main/xmen/cli), unit tests and documentation. We used the application for the first time to obtain SOTA results in the _Disease Text Mining Shared Task_ from the Barcelona Supercomputing Center. We presented the results in [this paper](https://link.springer.com/chapter/10.1007/978-3-031-42448-9_12#citeas) for the _International Conference of the Cross-Language Evaluation Forum for European Languages 2023_.

### [🔍 Novel NLP Evaluation Module Implementation for HuggingFace](https://huggingface.co/spaces/hpi-dhc/FairEval)
[Katrin Ortmann presented in 2022](https://aclanthology.org/2022.lrec-1.150) a new evaluation method that more accurately reflects true prediction quality for labeled span-based metrics. We thought the idea was fantastic, so I provided an implementation within the HuggingFace Evaluate module to democratize its use. It has already been of help in some workshops and shared tasks as []. Just follow the link to see the code!
 
### 🕵️ [Multi-modal Face Anti Spoofing](https://github.com/nachollorca/mm-FAS)
I developed an application to detect whether the face in front of the camera is real or fake (a print, a screen...) for a Kiosk manufacturing company. I use a CNN trained separately on RGB, infrared and depth information and test its performance on a self-recorded dataset, paying special attention to the effects of different conditions of room lighting or camera position. The depth model proves to be superior in most scenarios, notably obtaining 0.05 ACER score across all settings. 

### 🎻 [Music Genre Classification](https://github.com/nachollorca/musicator)
A fun little project where I attempt to classify songs within 10 music genres discussing different methods, from random forests to simple neural networks. 

### ➗ Mathematical Foundations of ML Algorithms 
My M. Sc. was very heavy on statistics. I have compiled some interesting implementations I did from scratch of various Machine Learning methods in jupyter notebooks. 
[🚧 under construction 🚧]

### 😐 [Facial Landmark Detection](https://github.com/nachollorca/facial-landmark-detection/): 
Old computer-vision application I developed with a couple of classmates on the use of CNNs to detect facial landmarks (points that define mouth, eyes, nose, eyebrows, etc.) for face recognition.

### 🟢 Others 
Some other smaller or shared projects. [🚧 under construction 🚧]
- 🦠 __Epidemiological Data Analysis in R-language__: I had access to a sweet German biomedical dataset, so here is a varied statistical analysis I performed to show my R skills.
- 💲 __Impact of Paid Subscriptions in Physician Platforms__: in 2020, I conducted an investigation with a couple classmates about whether paying a subscription has a significant effect on the ratings of medical physicians in the platform [Jameda](https://www.jameda.de/). 
- 🗃️ __ETL tools for Master Data Management__: brief literature survey of ETL and MDM with a fictional demonstration of some use cases.
