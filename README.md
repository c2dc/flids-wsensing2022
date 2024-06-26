# FL-IDS WSensing 2022

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Source Code of the Article “Combination of Models for Denial-Of-Service Classification
over Different Networks”, published in Workshop on Security, Privacy and Reliability on Wireless Sensing Networks -- WSensing 2022.

## How to cite 

To cite this work, use the following citation: 

```latex
@inproceedings{10.1145/3569902.3570176,
  author = {
    Melo, Leonardo H. and
    de Carvalho Bertoli,
    Gustavo and Saotome,
    Osamu and Domingues,
    Marcelo F. and Pereira Jr.,
    Louren\c{c}o Alves
  },
  title = {Combination of Models for Denial-Of-Service Classification over Different Networks},
  year = {2023},
  isbn = {9781450397377},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3569902.3570176},
  doi = {10.1145/3569902.3570176},
  abstract = {Due to the recent increase in the number of devices connected to different networks,
    information traffic has increased significantly. As a result of this, the number of threats has
    also increased. Thus, other works proposed intrusion detection systems (IDS) to protect sensitive
    user data. IDS are responsible for identifying malicious data flows and reporting possible attacks.
    However, the first IDS have based on detecting attacks on signatures. Therefore, IDS cannot keep
    up with the constant evolution of existing attacks. Hence, techniques such as Machine Learning (ML)
    have become allies of this system type to ensure its effectiveness. The use of ML represents a
    significant advance in the development of IDS, but there are still open questions about the ability
    to detect attacks on different isolated networks. Therefore, the present work proposes a Federated
    Learning (FL) scheme with sampling and attribute selection methods for Distributed Denial-Of-Service
    (DDoS) classification. Furthermore, we propose to combine the FL scheme with the Energy-based Flow
    Classifier (EFC) algorithm building an ensemble model capable of identifying malicious agents. We
    evaluated whether using an ensemble can extract different types of information during the ML process.
    This work represents ongoing research with results under development.
  },
  booktitle = {Proceedings of the 11th Latin-American Symposium on Dependable Computing},
  pages = {137–142},
  numpages = {6},
  keywords = {network intrusion detection, federated learning, ensemble, denial of service},
  location = {, Fortaleza/CE, Brazil, },
  series = {LADC '22}
}
```

## Create the Experimental Environment

To create the experimental environment, execute the following commands: 

```sh
python -m venv .env 
```

After creating the Virtual environment, use the following command to install the necessary python packages: 

```sh
pip install -r requirements.txt
```

## References 

The data used to carry out the experiments can be obtained from:

[Machine Learning-Based NIDS Datasets (Netflow V2 Datasets)](https://staff.itee.uq.edu.au/marius/NIDS_datasets/) 

The following project was used as a reference for the preparation of this work:

[Energy-based Flow Classifier](https://github.com/EnergyBasedFlowClassifier/EFC-package)


## Authors 

<a href="https://github.com/leonardohdemelo"><img src="https://avatars0.githubusercontent.com/u/43916660?s=460&v=4" alt="drawing" width="40" align="middle"/></a>
&nbsp;&nbsp;&nbsp;Leonardo Henrique de Melo 

<a href="https://github.com/gubertoli"><img src="https://avatars.githubusercontent.com/u/4803756?v=4" alt="drawing" width="40" align="middle"/></a>
&nbsp;&nbsp;&nbsp;Gustavo de Carvalho Bertoli 

<a href="https://scholar.google.com/citations?user=UDMjlccAAAAJ&hl=en"><img src="https://scholar.googleusercontent.com/citations?view_op=view_photo&user=UDMjlccAAAAJ&citpid=2" alt="drawing" width="40" align="middle"/></a>
&nbsp;&nbsp;&nbsp;Osamu Saotome

<a href="https://github.com/MarFerDom"><img src="https://avatars.githubusercontent.com/u/16342417?v=4" alt="drawing" width="40" align="middle"/></a>
&nbsp;&nbsp;&nbsp;Marcelo F. Domingues 

<a href="https://github.com/ljr"><img src="https://avatars.githubusercontent.com/u/978047?v=4" alt="drawing" width="40" align="middle"/></a>
&nbsp;&nbsp;&nbsp;Lourenço Alves Pereira Jr. 
