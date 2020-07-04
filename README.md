# Awesome-Federated-Learning

A curated list of federated learning publications, reorgnized from Arxiv.

<strong>Last Update: July 3rd, 2020</strong>.	

## Research Areas, Paper Category
 - [Distributed Optimization](#Distributed-optimization)
 - [Non-IID and Model Personalization](#Non-IID-and-Model-Personalization)
 - [Neural Architecture Search](#Neural-Architecture-Search)
 - [Semi-Supervised Learning](#Semi-Supervised-Learning)
 - [Communication Compression](#Communication-Compression)
 - [Wireless Communication and Fog Computing](#Wireless-Communication-and-Fog-Computing-and-Internet-Of-Things)
 - [Computation Efficiency](#Computation-Efficiency)
 - [Adversarial Attacks](#Adversarial-Attacks)
 - [Privacy](#Privacy)
 - [Fairness](#Fairness)
 - [FL System](#FL-System)
 - [Models and Applications](#Models-and-Applications)
 - [Benchmark and Dataset](#Benchmark-and-Dataset)
 - [Survey](#Survey)

## Distributed optimization
Local Stochastic Approximation: A Unified View of Federated Learning and Distributed Multi-Task Reinforcement Learning Algorithms
https://arxiv.org/pdf/2006.13460.pdf

Researcher: 
Thinh T. Doan
https://sites.google.com/site/thinhdoan210/home

Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning
https://arxiv.org/pdf/2005.06105.pdf

Exact Support Recovery in Federated Regression with One-shot Communication
https://arxiv.org/pdf/2006.12583.pdf

DEED: A General Quantization Scheme for Communication Efficiency in Bits
https://arxiv.org/pdf/2006.11401.pdf
Researcher: Ruoyu Sun, UIUC

Robust Federated Learning: The Case of Affine Distribution Shifts
https://arxiv.org/pdf/2006.08907.pdf
Researcher: Ramtin Pedarsani, UCSB
Amirhossein Reisizadeh, PhD, UCSB

Personalized Federated Learning with Moreau Envelopes
https://arxiv.org/pdf/2006.08848.pdf

Towards Flexible Device Participation in Federated Learning for Non-IID Data
https://arxiv.org/pdf/2006.06954.pdf
Keywords: inactive or return incomplete updates in non-IID dataset

A Primal-Dual SGD Algorithm for Distributed Nonconvex Optimization
https://arxiv.org/pdf/2006.03474.pdf

FedPD: A Federated Learning Framework with Optimal Rates and Adaptivity to Non-IID Data
https://arxiv.org/pdf/2005.11418.pdf
Researcher: Wotao Yin, UCLA

FedSplit: An algorithmic framework for fast federated optimization
https://arxiv.org/pdf/2005.05238.pdf

Distributed Stochastic Non-Convex Optimization: Momentum-Based Variance Reduction
https://arxiv.org/pdf/2005.00224.pdf

On the Outsized Importance of Learning Rates in Local Update Methods
https://arxiv.org/pdf/2007.00878.pdf
Highlight: local model learning rate optimization + automation
Researcher: Jakub

Federated Learning with Compression: Unified Analysis and Sharp Guarantees
https://arxiv.org/pdf/2007.01154.pdf
Highlight: non-IID, gradient compression + local SGD
Researcher: Mehrdad Mahdavi, Jin Rong’s PhD http://www.cse.psu.edu/~mzm616/

From Local SGD to Local Fixed-Point Methods for Federated Learning
https://arxiv.org/pdf/2004.01442.pdf

Federated Residual Learning. 2020-03
https://arxiv.org/pdf/2003.12880.pdf

Adaptive Federated Optimization. ICML 2020. 2020-02-29
https://arxiv.org/pdf/2003.00295.pdf

Acceleration for Compressed Gradient Descent in Distributed and Federated Optimization. ICML 2020.
https://arxiv.org/pdf/2002.11364.pdf

LASG: Lazily Aggregated Stochastic Gradients for Communication-Efficient Distributed Learning
https://arxiv.org/pdf/2002.11360.pdf

## Non-IID and Model Personalization

FedCD: Improving Performance in non-IID Federated Learning. 2020
https://arxiv.org/pdf/2006.09637.pdf

Life Long Learning: FedFMC: Sequential Efficient Federated Learning on Non-iid Data. 2020
https://arxiv.org/pdf/2006.10937.pdf

Robust Federated Learning: The Case of Affine Distribution Shifts. 2020
https://arxiv.org/pdf/2006.08907.pdf

Personalized Federated Learning with Moreau Envelopes. 2020
https://arxiv.org/pdf/2006.08848.pdf

Ensemble Distillation for Robust Model Fusion in Federated Learning. 2020
https://arxiv.org/pdf/2006.07242.pdf
Researcher: Tao Lin, ZJU, EPFL https://tlin-tao-lin.github.io/index.html

Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning. 2020
https://arxiv.org/pdf/2005.06105.pdf

Towards Flexible Device Participation in Federated Learning for Non-IID Data. 2020
https://arxiv.org/pdf/2006.06954.pdf
Keywords: inactive or return incomplete updates in non-IID dataset

XOR Mixup: Privacy-Preserving Data Augmentation for One-Shot Federated Learning. 2020
https://arxiv.org/pdf/2006.05148.pdf


NeurIPS 2020 submission: An Efficient Framework for Clustered Federated Learning. 2020
https://arxiv.org/pdf/2006.04088.pdf
Researcher: AVISHEK GHOSH, UCB, PhD

Continual Local Training for Better Initialization of Federated Models. 2020
https://arxiv.org/pdf/2005.12657.pdf

FedPD: A Federated Learning Framework with Optimal Rates and Adaptivity to Non-IID Data. 2020
https://arxiv.org/pdf/2005.11418.pdf
Researcher: Wotao Yin, UCLA

Global Multiclass Classification from Heterogeneous Local Models. 2020
https://arxiv.org/pdf/2005.10848.pdf
Researcher: Stanford https://stanford.edu/~pilanci/

Multi-Center Federated Learning. 2020
https://arxiv.org/pdf/2005.01026.pdf

Federated learning with hierarchical clustering of local updates to improve training on non-IID data. 2020
https://arxiv.org/pdf/2004.11791.pdf

Federated Learning with Only Positive Labels. 2020
https://arxiv.org/pdf/2004.10342.pdf
Researcher: Felix Xinnan Yu, Google New York
Keywords: positive labels
Limited Labels

Federated Semi-Supervised Learning with Inter-Client Consistency. 2020
https://arxiv.org/pdf/2006.12097.pdf

(*) FedMAX: Mitigating Activation Divergence for Accurate and Communication-Efficient Federated Learning. CMU ECE. 2020-04-07
https://arxiv.org/pdf/2004.03657.pdf

(*) Adaptive Personalized Federated Learning
https://arxiv.org/pdf/2003.13461.pdf

Semi-Federated Learning
https://arxiv.org/pdf/2003.12795.pdf

Survey of Personalization Techniques for Federated Learning. 2020-03-19
https://arxiv.org/pdf/2003.08673.pdf

Device Heterogeneity in Federated Learning: A Superquantile Approach. 2020-02
https://arxiv.org/pdf/2002.11223.pdf

Personalized Federated Learning for Intelligent IoT Applications: A Cloud-Edge based Framework
https://arxiv.org/pdf/2002.10671.pdf

Three Approaches for Personalization with Applications to Federated Learning
https://arxiv.org/pdf/2002.10619.pdf


## Neural Architecture Search
FedNAS: Federated Deep Learning via Neural Architecture Search. CVPR 2020. 2020-04-18
https://arxiv.org/abs/2004.08546

Real-time Federated Evolutionary Neural Architecture Search. 2020-03
https://arxiv.org/pdf/2003.02793.pdf

Differentially-private Federated Neural Architecture Search. 2020-06
https://arxiv.org/pdf/2006.10559.pdf

Federated Neural Architecture Search. 2020-06-14
https://arxiv.org/abs/2002.06352

## Transfer Learning
Decentralized Differentially Private Segmentation with PATE. 2020-04
https://arxiv.org/pdf/2004.06567.pdf \
Highlights: apply the ICLR 2017 paper "Semisupervised knowledge transfer for deep learning from private training data"

Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning. 2020
https://arxiv.org/pdf/2005.06105.pdf

## Continual Learning
Federated Continual Learning with Adaptive Parameter Communication. 2020-03
https://arxiv.org/pdf/2003.03196.pdf

## Semi-Supervised Learning
Semisupervised knowledge transfer for deep learning from private training data. ICLR 2017
https://arxiv.org/pdf/1610.05755.pdf

Scalable private learning with PATE. ICLR 2018. 
https://arxiv.org/abs/1802.08908

Federated Semi-Supervised Learning with Inter-Client Consistency. 2020
https://arxiv.org/pdf/2006.12097.pdf

## Communication Compression
NeurIPS 2020 submission: Artemis: tight convergence guarantees for bidirectional compression in Federated Learning. 2020
https://arxiv.org/pdf/2006.14591.pdf

Scheduling Policy and Power Allocation for Federated Learning in NOMA Based MEC
https://arxiv.org/pdf/2006.13044.pdf

Federated Mutual Learning
https://arxiv.org/pdf/2006.16765.pdf

A Better Alternative to Error Feedback for Communication-Efficient Distributed Learning
https://arxiv.org/pdf/2006.11077.pdf
Researcher: Peter Richtárik

Federated Learning With Quantized Global Model Updates
https://arxiv.org/pdf/2006.10672.pdf
Researcher: Mohammad Mohammadi Amiri, Princeton, Information Theory and Machine Learning

Federated Learning with Compression: Unified Analysis and Sharp Guarantees
https://arxiv.org/pdf/2007.01154.pdf
Highlight: non-IID, gradient compression + local SGD
Researcher: Mehrdad Mahdavi, Jin Rong’s PhD http://www.cse.psu.edu/~mzm616/

Evaluating the Communication Efficiency in Federated Learning Algorithm
https://arxiv.org/pdf/2004.02738.pdf

Dynamic Sampling and Selective Masking for Communication-Efficient Federated Learning
https://arxiv.org/pdf/2003.09603.pdf

Ternary Compression for Communication-Efficient Federated Learning
https://arxiv.org/pdf/2003.03564.pdf

Gradient Statistics Aware Power Control for Over-the-Air Federated Learning
https://arxiv.org/pdf/2003.02089.pdf

## Wireless Communication and Fog Computing and Internet Of Things
Researcher: 
H. Vincent Poor
https://ee.princeton.edu/people/h-vincent-poor

Hao Ye
https://scholar.google.ca/citations?user=ok7OWEAAAAAJ&hl=en

Ye Li
http://liye.ece.gatech.edu/

Mix2FLD: Downlink Federated Learning After Uplink Federated Distillation With Two-Way Mixup
https://arxiv.org/pdf/2006.09801.pdf
Researcher: Mehdi Bennis, Seong-Lyun Kim

Wireless Communications for Collaborative Federated Learning in the Internet of Things
https://arxiv.org/pdf/2006.02499.pdf

Democratizing the Edge: A Pervasive Edge Computing Framework
https://arxiv.org/pdf/2007.00641.pdf

UVeQFed: Universal Vector Quantization for Federated Learning
https://arxiv.org/pdf/2006.03262.pdf

Federated Deep Learning Framework For Hybrid Beamforming in mm-Wave Massive MIMO
https://arxiv.org/pdf/2005.09969.pdf

Efficient Federated Learning over Multiple Access Channel with Differential Privacy Constraints
https://arxiv.org/pdf/2005.07776.pdf

A Secure Federated Learning Framework for 5G Networks
https://arxiv.org/pdf/2005.05752.pdf

Federated Learning and Wireless Communications
https://arxiv.org/pdf/2005.05265.pdf

Lightwave Power Transfer for Federated Learning-based Wireless Networks
https://arxiv.org/pdf/2005.03977.pdf

Towards Ubiquitous AI in 6G with Federated Learning
https://arxiv.org/pdf/2004.13563.pdf

Optimizing Over-the-Air Computation in IRS-Aided C-RAN Systems
https://arxiv.org/pdf/2004.09168.pdf

Network-Aware Optimization of Distributed Learning for Fog Computing
https://arxiv.org/pdf/2004.08488.pdf

On the Design of Communication Efficient Federated Learning over Wireless Networks
https://arxiv.org/pdf/2004.07351.pdf

Federated Machine Learning for Intelligent IoT via Reconfigurable Intelligent Surface
https://arxiv.org/pdf/2004.05843.pdf

Client Selection and Bandwidth Allocation in Wireless Federated Learning Networks: A Long-Term Perspective
https://arxiv.org/pdf/2004.04314.pdf

Resource Management for Blockchain-enabled Federated Learning: A Deep Reinforcement Learning Approach
https://arxiv.org/pdf/2004.04104.pdf

A Blockchain-based Decentralized Federated Learning Framework with Committee Consensus
https://arxiv.org/pdf/2004.00773.pdf

Scheduling for Cellular Federated Edge Learning with Importance and Channel. 2020-04
https://arxiv.org/pdf/2004.00490.pdf

Differentially Private Federated Learning for Resource-Constrained Internet of Things. 2020-03
https://arxiv.org/pdf/2003.12705.pdf

Federated Learning for Task and Resource Allocation in Wireless High Altitude Balloon Networks. 2020-03
https://arxiv.org/pdf/2003.09375.pdf

Gradient Estimation for Federated Learning over Massive MIMO Communication Systems
https://arxiv.org/pdf/2003.08059.pdf

Adaptive Federated Learning With Gradient Compression in Uplink NOMA
https://arxiv.org/pdf/2003.01344.pdf

Performance Analysis and Optimization in Privacy-Preserving Federated Learning
https://arxiv.org/pdf/2003.00229.pdf

Energy-Efficient Federated Edge Learning with Joint Communication and Computation Design
https://arxiv.org/pdf/2003.00199.pdf

Federated Over-the-Air Subspace Learning and Tracking from Incomplete Data
https://arxiv.org/pdf/2002.12873.pdf

Decentralized Federated Learning via SGD over Wireless D2D Networks
https://arxiv.org/pdf/2002.12507.pdf

HFEL: Joint Edge Association and Resource Allocation for Cost-Efficient Hierarchical Federated Edge Learning
https://arxiv.org/pdf/2002.11343.pdf


## Computation Efficiency
NeurIPS 2020 Submission: Distributed Learning on Heterogeneous Resource-Constrained Devices
https://arxiv.org/pdf/2006.05403.pdf


SplitFed: When Federated Learning Meets Split Learning
https://arxiv.org/pdf/2004.12088.pdf

Lottery Hypothesis based Unsupervised Pre-training for Model Compression in Federated Learning
https://arxiv.org/pdf/2004.09817.pdf

Secure Federated Learning in 5G Mobile Networks. 2020/04
https://arxiv.org/pdf/2004.06700.pdf 

## Adversarial Attacks
Legal Risks of Adversarial Machine Learning Research
https://arxiv.org/pdf/2006.16179.pdf

FDA3 : Federated Defense Against Adversarial Attacks for Cloud-Based IIoT Applications
https://arxiv.org/pdf/2006.15632.pdf

Byzantine-Resilient High-Dimensional SGD with Local Iterations on Heterogeneous Data
https://arxiv.org/pdf/2006.13041.pdf
Researcher: Suhas Diggavi, UCLA (https://scholar.google.com/citations?hl=en&user=hjTzNuQAAAAJ&view_op=list_works&sortby=pubdate)

NeurIPS 2020 submission: Free-rider Attacks on Model Aggregation in Federated Learning
https://arxiv.org/pdf/2006.11901.pdf

FedMGDA+: Federated Learning meets Multi-objective Optimization
https://arxiv.org/pdf/2006.11489.pdf

Communication-Efficient Robust Federated Learning Over Heterogeneous Datasets
https://arxiv.org/pdf/2006.09992.pdf

Robust Federated Recommendation System
https://arxiv.org/pdf/2006.08259.pdf

Federated Recommendation System via Differential Privacy
https://arxiv.org/pdf/2005.06670.pdf

NeurIPS 2020 Submission: Backdoor Attacks on Federated Meta-Learning
https://arxiv.org/pdf/2006.07026.pdf
Researcher: Chien-Lun Chen, USC

Distributed Differentially Private Averaging with Improved Utility and Robustness to Malicious Parties
https://arxiv.org/pdf/2006.07218.pdf

Secure Byzantine-Robust Machine Learning
https://arxiv.org/pdf/2006.04747.pdf

Exploiting Defenses against GAN-Based Feature Inference Attacks in Federated Learning
https://arxiv.org/pdf/2004.12571.pdf

A Framework for Evaluating Gradient Leakage Attacks in Federated Learning
https://arxiv.org/pdf/2004.10397.pdf
Researcher: Wenqi Wei, Ling Liu, GaTech

Data Poisoning Attacks on Federated Machine Learning
https://arxiv.org/pdf/2004.10020.pdf

Towards Realistic Byzantine-Robust Federated Learning
https://arxiv.org/pdf/2004.04986.pdf

An Overview of Federated Deep Learning Privacy Attacks and Defensive Strategies
https://arxiv.org/pdf/2004.04676.pdf

Privacy-preserving Weighted Federated Learning within Oracle-Aided MPC Framework
https://arxiv.org/pdf/2003.07630.pdf

BASGD: Buffered Asynchronous SGD for Byzantine Learning
https://arxiv.org/pdf/2003.00937.pdf

Stochastic-Sign SGD for Federated Learning with Theoretical Guarantees
https://arxiv.org/pdf/2002.10940.pdf


## Privacy
GS-WGAN: A Gradient-Sanitized Approach for Learning Differentially Private Generators
https://arxiv.org/pdf/2006.08848.pdf

Privacy For Free: Wireless Federated Learning Via Uncoded Transmission With Adaptive Power Control
https://arxiv.org/pdf/2006.05459.pdf

ARIANN: Low-Interaction Privacy-Preserving Deep Learning via Function Secret Sharing
https://arxiv.org/pdf/2006.04593.pdf

LDP-Fed: Federated Learning with Local Differential Privacy
https://arxiv.org/pdf/2006.03637.pdf
Researcher: Ling Liu, GaTech

A Distributed Trust Framework for Privacy-Preserving Machine Learning
https://arxiv.org/pdf/2006.02456.pdf

Efficient Privacy Preserving Edge Computing Framework for Image Classification
https://arxiv.org/pdf/2005.04563.pdf

Information-Theoretic Bounds on the Generalization Error and Privacy Leakage in Federated Learning
https://arxiv.org/pdf/2005.02503.pdf

Local Differential Privacy based Federated Learning for Internet of Things
https://arxiv.org/pdf/2004.08856.pdf

Exploring Private Federated Learning with Laplacian Smoothing
https://arxiv.org/pdf/2005.00218.pdf

Privacy Preserving Distributed Machine Learning with Federated Learning
https://arxiv.org/pdf/2004.12108.pdf

Enhancing Privacy via Hierarchical Federated Learning
https://arxiv.org/pdf/2004.11361.pdf

Asymmetrical Vertical Federated Learning
https://arxiv.org/pdf/2004.07427.pdf
Researcher: Tencent Cloud, Libin Wang

Decentralized Differentially Private Segmentation with PATE. 2020-04
https://arxiv.org/pdf/2004.06567.pdf \
Highlights: apply the ICLR 2017 paper "Semisupervised knowledge transfer for deep learning from private training data"

Differentially Private AirComp Federated Learning with Power Adaptation Harnessing Receiver Noise. 2020-04. https://arxiv.org/pdf/2004.06337.pdf

PrivFL: Practical Privacy-preserving Federated Regressions on High-dimensional Data over Mobile Networks
https://arxiv.org/pdf/2004.02264.pdf

Inverting Gradients - How easy is it to break privacy in federated learning?
https://arxiv.org/pdf/2003.14053.pdf

Learn to Forget: User-Level Memorization Elimination in Federated Learning
https://arxiv.org/pdf/2003.10933.pdf

FedSel: Federated SGD under Local Differential Privacy with Top-k Dimension Selection
https://arxiv.org/pdf/2003.10637.pdf

Decentralized Policy-Based Private Analytics
https://arxiv.org/pdf/2003.06612.pdf

Practical and Bilateral Privacy-preserving Federated Learning
https://arxiv.org/pdf/2002.09843.pdf

## Fairness

Hierarchically Fair Federated Learning
https://arxiv.org/pdf/2004.10386.pdf

## incentive mechanism
FMore: An Incentive Scheme of Multi-dimensional Auction for Federated Learning in MEC. ICDCS 2020
https://arxiv.org/pdf/2002.09699.pdf

## Models and Applications

# Models
Discrete-Time Cox Models
https://arxiv.org/pdf/2006.08997.pdf

GAN
Federated Generative Adversarial Learning
https://arxiv.org/pdf/2005.03793.pdf

### Natural language Processing
generative sequence models (e.g., language models)
https://arxiv.org/pdf/2006.07490.pdf

Pretraining Federated Text Models for Next Word Prediction
https://arxiv.org/pdf/2005.04828.pdf

FedNER: Privacy-preserving Medical Named Entity Recognition with Federated Learning. MSRA. 2020-03.
https://arxiv.org/pdf/2003.09288.pdf

### Computer Vision
Federated Face Anti-spoofing
https://arxiv.org/pdf/2005.14638.pdf

(*) Federated Visual Classification with Real-World Data Distribution. MIT. ECCV 2020. 2020-03
https://arxiv.org/pdf/2003.08082.pdf

### Health Care: 
Privacy-Preserving Technology to Help Millions of People: Federated Prediction Model for Stroke Prevention
https://arxiv.org/pdf/2006.10517.pdf

A Federated Learning Framework for Healthcare IoT devices
https://arxiv.org/pdf/2005.05083.pdf
Keywords: Split Learning + Sparsification

Federated Transfer Learning for EEG Signal Classification
https://arxiv.org/pdf/2004.12321.pdf

The Future of Digital Health with Federated Learning
https://arxiv.org/pdf/2003.08119.pdf

### Transportation (Internet of Vehicles):
Federated Learning for Vehicular Networks
https://arxiv.org/pdf/2006.01412.pdf

Towards Federated Learning in UAV-Enabled Internet of Vehicles: A Multi-Dimensional Contract-Matching Approach
https://arxiv.org/pdf/2004.03877.pdf

Federated Learning Meets Contract Theory: Energy-Efficient Framework for Electric Vehicle Networks
https://arxiv.org/pdf/2004.01828.pdf

Beyond privacy regulations: an ethical approach to data usage in transportation. TomTom. 2020-04-01
https://arxiv.org/pdf/2004.00491.pdf

Privacy-preserving Traffic Flow Prediction: A Federated Learning Approach
https://arxiv.org/pdf/2003.08725.pdf

Communication-Efficient Massive UAV Online Path Control: Federated Learning Meets Mean-Field Game Theory. 2020-03
https://arxiv.org/pdf/2003.04451.pdf

FedLoc: Federated Learning Framework for Data-Driven Cooperative Localization and Location Data Processing. 2020-03
https://arxiv.org/pdf/2003.03697.pdf

Practical Privacy Preserving POI Recommendation
https://arxiv.org/pdf/2003.02834.pdf

### Speech Recognition:
Training Keyword Spotting Models on Non-IID Data with Federated Learning
https://arxiv.org/pdf/2005.10406.pdf

### Smart City
Cloud-based Federated Boosting for Mobile Crowdsensing
https://arxiv.org/pdf/2005.05304.pdf

### Recommendation System
(*) Federated Multi-view Matrix Factorization for Personalized Recommendations
https://arxiv.org/pdf/2004.04256.pdf

Robust Federated Recommendation System
https://arxiv.org/pdf/2006.08259.pdf

Federated Recommendation System via Differential Privacy
https://arxiv.org/pdf/2005.06670.pdf

FedRec: Privacy-Preserving News Recommendation with Federated Learning. MSRA. 2020-03
https://arxiv.org/pdf/2003.09592.pdf

Federating Recommendations Using Differentially Private Prototypes
https://arxiv.org/pdf/2003.00602.pdf

### Anomaly Detection
An On-Device Federated Learning Approach for Cooperative Anomaly Detection
https://arxiv.org/pdf/2002.12301.pdf

### Financial Industry
FedCoin: A Peer-to-Peer Payment System for Federated Learning
https://arxiv.org/pdf/2002.11711.pdf

## Benchmark and Dataset

The OARF Benchmark Suite: Characterization and Implications for Federated Learning Systems
https://arxiv.org/pdf/2006.07856.pdf

Evaluation Framework For Large-scale Federated Learning
https://arxiv.org/pdf/2003.01575.pdf

## FL System
A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection
https://arxiv.org/pdf/1907.09693.pdf

FLeet: Online Federated Learning via Staleness Awareness and Performance Prediction
https://arxiv.org/pdf/2006.07273.pdf
Researcher: Georgios Damaskinos, MLSys, https://people.epfl.ch/georgios.damaskinos?lang=en

Heterogeneity-Aware Federated Learning
https://arxiv.org/pdf/2006.06983.pdf
Researcher: Mengwei Xu, PKU

Responsive Web User Interface to Recover Training Data from User Gradients in Federated Learning
https://ldp-machine-learning.herokuapp.com/

Decentralised Learning from Independent Multi-Domain Labels for Person Re-Identification
https://arxiv.org/pdf/2006.04150.pdf

[startup] Industrial Federated Learning -- Requirements and System Design
https://arxiv.org/pdf/2005.06850.pdf

[startup] Federated Learning and Differential Privacy: Software tools analysis, the Sherpa.ai FL framework and methodological guidelines for preserving data privacy
https://arxiv.org/pdf/2007.00914.pdf

## Survey

A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection
https://arxiv.org/pdf/1907.09693.pdf

Researcher: Bingsheng He, NUS
Qinbin Li, PhD, NUS, HKUST
https://qinbinli.com/files/CV_QB.pdf

SECure: A Social and Environmental Certificate for AI Systems
https://arxiv.org/pdf/2006.06217.pdf

From Federated Learning to Fog Learning: Towards Large-Scale Distributed Machine Learning in Heterogeneous Wireless Networks
https://arxiv.org/pdf/2006.03594.pdf

Federated Learning for 6G Communications: Challenges, Methods, and Future Directions
https://arxiv.org/pdf/2006.02931.pdf

A Review of Privacy Preserving Federated Learning for Private IoT Analytics
https://arxiv.org/pdf/2004.11794.pdf

Survey of Personalization Techniques for Federated Learning. 2020-03-19
https://arxiv.org/pdf/2003.08673.pdf

Threats to Federated Learning: A Survey
https://arxiv.org/pdf/2003.02133.pdf

Towards Utilizing Unlabeled Data in Federated Learning: A Survey and Prospective
https://arxiv.org/pdf/2002.11545.pdf

Federated Learning for Resource-Constrained IoT Devices: Panoramas and State-of-the-art
https://arxiv.org/pdf/2002.10610.pdf
