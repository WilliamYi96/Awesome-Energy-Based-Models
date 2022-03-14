# Awesome-Energy-Based-Models
Selected papers I've read in the field of zero shot learning. Not a complete list of all accepted papers. I'll mainly focus on those papers with open-source implementations and most interesting to me. 

**Note**: *This list may contain understanding bias and personal preference. All that papers without available code will not provide a link to it.*

## Table of Contents
+ [Papers](#Papers)                            

### Papers      
#### arXiv
+ **ESVGD**: Learning Equivariant Energy Based Models with Equivariant Stein Variational Gradient Descent. Priyank Jaini, Lars Holdijk, Max Welling. (2106) [[paper]](https://arxiv.org/abs/2106.07832)
+ **Shallow-NN**: On Energy-Based Models with Overparametrized Shallow Neural Networks. Carles Domingo-Enrich, Alberto Bietti, Eric Vanden-Eijnden, Joan Bruna. (2104) [[paper]](https://arxiv.org/abs/2104.07531) [[code]](https://github.com/CDEnrich/ebms_shallow_nn)
+ How to Train Your Energy-Based Models. Yang Song, Diederik P. Kingma. (2101) [[paper]](https://arxiv.org/abs/2101.03288) 
+ **ScoreFlow**: Maximum Likelihood Training of Score-Based Diffusion Models. Yang Song, Conor Durkan, Iain Murray, Stefano Ermon. (2101) [[paper]](https://arxiv.org/abs/2101.09258)
+ SE(3)-Equivariant Energy-based Models for End-to-End Protein Folding. Jiaxiang Wu, Tao Shen, Haidong Lan, Yatao Bian, Junzhou Huang. (2106-biorxiv)
+ Energy-Based Learning for Cooperative Games, with Applications to Feature/Data/Model Valuations. Yatao Bian, Yu Rong, Tingyang Xu, Jiaxiang Wu, Andreas Krause, Junzhou Huang.
+ Hybrid Discriminative-Generative Training via Contrastive Learning. Hao Liu, Pieter Abbeel. (2007)
+ Denoising Diffusion Probabilistic Models. Jonathan Ho, Ajay Jain, Pieter Abbeel. (2006)
+ Energy-Based Models for Continual Learning. Shuang Li, Yilun Du, Gido M. van de Ven, Igor Mordatch. (2011)

#### ICLR 2022
+ SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations. ICLR, 2022.
+ Score-Based Generative Modeling with Critically-Damped Langevin Diffusion. ICLR, 2022.

#### ICML 2021
+ Latent Space Energy-Based Model of Symbol-Vector Coupling for Text Generation and Classification. Bo Pang, Ying Nian Wu. 
+ Variational (Gradient) Estimate of the Score Function in Energy-based Latent Variable Models. Fan Bao, Kun Xu, Chongxuan Li, Lanqing Hong, Jun Zhu, Bo Zhang. 
+ On Energy-Based Models with Overparametrized Shallow Neural Networks.Carles Domingo-Enrich, Alberto Bietti, Eric Vanden-Eijnden, Joan Bruna. 
+ Improved Contrastive Divergence Training of Energy-Based Models. Yilun Du, Shuang Li, Josh Tenenbaum, Igor Mordatch. 
+ Conjugate Energy-Based Models. Hao Wu, Babak Esmaeili, Michael Wick, Jean-Baptiste Tristan, Jan-Willem van de Meent. 
+ Adversarial purification with Score-based generative models. Jongmin Yoon, Sung Ju Hwang, Juho Lee.
+ Learning Gradient Fields for Molecular Conformation Generation (long talk). Chence Shi, Shitong Luo, Minkai Xu, Jian Tang.
+ Variational (Gradient) Estimate of the Score Function in Energy-based Latent Variable Models. Fan Bao, Kun Xu, Chongxuan Li, Lanqing Hong, Jun Zhu, Bo Zhang. (2010)
+ 
#### CVPR 2021
+ Patchwise Generative ConvNet: Training Energy-Based Models From a Single Natural Image for Internal Learning (oral). Zilong Zheng, Jianwen Xie, Ping Li.
+ Energy-Based Learning for Scene Graph Generation (best paper candidate). Mohammed Suhail, Abhay Mittal, Behjat Siddiquie, Chris Broaddus, Jayan Eledath, Gerard Medioni, Leonid Sigal.
+ Trajectory Prediction With Latent Belief Energy-Based Model. Bo Pang, Tianyang Zhao, Xu Xie, Ying Nian Wu.
+ Generative PointNet: Deep Energy-Based Learning on Unordered Point Sets for 3D Generation, Reconstruction and Classification. Jianwen Xie, Yifei Xu, Zilong Zheng, Song-Chun Zhu, Ying Nian Wu.


#### ICLR 2021
+ VAEBM: A Symbiosis between Variational Autoencoders and Energy-based Models. (spotlight) Zhisheng Xiao, Karsten Kreis, Jan Kautz, Arash Vahdat.
+ No MCMC for me: Amortized sampling for fast and stable training of energy-based models. Will Sussman Grathwohl, Jacob Jin Kelly, Milad Hashemi, Mohammad Norouzi, Kevin Swersky, David Duvenaud. 
+ Learning Energy-Based Generative Models via Coarse-to-Fine Expanding and Sampling. Yang Zhao, Jianwen Xie, Ping Li. 
+ DINO: A Conditional Energy-Based GAN for Domain Translation. Konstantinos Vougioukas, Stavros Petridis, Maja Pantic.
+ Generalized Energy Based Models. Michael Arbel, Liang Zhou, Arthur Gretton.
+ Stochastic Security: Adversarial Defense Using Long-Run Dynamics of Energy-Based Models. Mitch Hill, Jonathan Craig Mitchell, Song-Chun Zhu.
+ Learning Energy-Based Models by Diffusion Recovery Likelihood. Ruiqi Gao, Yang Song, Ben Poole, Ying Nian Wu, Diederik P Kingma.
+ GraphEBM: Molecular Graph Generation with Energy-Based Models (workshop). Meng Liu, Keqiang Yan, Bora Oztekin, Shuiwang Ji.
+ Score-Based Generative Modeling through Stochastic Differential Equations (oral). Yang Song, Jascha Sohl-Dickstein, Diederik P. Kingma, Abhishek Kumar, Stefano Ermon, Ben Poole.
+ 
#### AAAI 2021
+ Learning Energy-Based Model with Variational Auto-Encoder as Amortized Sampler. Jianwen Xie, Zilong Zheng, Ping Li.

#### NeurIPS 2020
+ Bi-level Score Matching for Learning Energy-based Latent Variable Models. Fan Bao, Chongxuan LI, Kun Xu, Hang Su, Jun Zhu, Bo Zhang.
+ Energy-based Out-of-distribution Detection. Weitang Liu, Xiaoyun Wang, John Owens, Sharon Li.
+ Your GAN is Secretly an Energy-based Model and You Should Use Discriminator Driven Latent Sampling. Tong Che, Ruixiang ZHANG, Jascha Sohl-Dickstein, Hugo Larochelle, Liam Paull, Yuan Cao, Yoshua Bengio.
+ Deep Energy-based Modeling of Discrete-Time Physics. Takashi Matsubara, Ai Ishikawa, Takaharu Yaguchi.
+ Strictly Batch Imitation Learning by Energy-based Distribution Matching. Daniel Jarrett, Ioana Bica, Mihaela van der Schaar.
+ ICE-BeeM: Identifiable Conditional Energy-Based Deep Models Based on Nonlinear ICA. Ilyes Khemakhem, Ricardo Monti, Diederik P. Kingma, Aapo Hyvarinen.
+ Learning Discrete Energy-based Models via Auxiliary-variable Local Exploration. Hanjun Dai, Rishabh Singh, Bo Dai, Charles Sutton, Dale Schuurmans.
+ Learning Latent Space Energy-Based Prior Model. Bo Pang, Tian Han, Erik Nijkamp, Song-Chun Zhu, Ying Nian Wu.
+ Unsupervised Joint k-node Graph Representations with Compositional Energy-Based Models. Leonardo Cotta, Carlos H. C. Teixeira, Ananthram Swami, Bruno Ribeiro.
+ Autoregressive Score Matching. Chenlin Meng, Lantao Yu, Yang Song, Jiaming Song, Stefano Ermon.
+ Improved Techniques for Training Score-Based Generative Models. Yang Song, Stefano Ermon.
+ Unsupervised Joint k-node Graph Representations with Compositional Energy-Based Models. Leonardo Cotta, Carlos H. C. Teixeira, Ananthram Swami, Bruno Ribeiro.
+ Learning Latent Space Energy-Based Prior Model. Bo Pang, Tian Han, Erik Nijkamp, Song-Chun Zhu, Ying Nian Wu.
+ Efficient Learning of Generative Models via Finite-Difference Score Matching. Tianyu Pang, Kun Xu, Chongxuan Li, Yang Song, Stefano Ermon, Jun Zhu. [[paper]](https://arxiv.org/abs/2007.03317)
#### ECCV 2020
+ Energy-Based Models for Deep Probabilistic Regression. Fredrik K. Gustafsson, Martin Danelljan, Goutam Bhat, Thomas B. Schön.
+ How to Train Your Energy-Based Model for Regression (together, BMVC20). Fredrik K. Gustafsson, Martin Danelljan, Radu Timofte, Thomas B. Schön.
+ Learning Gradient Fields for Shape Generation (spotlight). Ruojin Cai, Guandao Yang, Hadar Averbuch-Elor, Zekun Hao, Serge Belongie, Noah Snavely, Bharath Hariharan.
#### AISTATS 2020
+ Permutation Invariant Graph Generation via Score-Based Generative Modeling. Chenhao Niu, Yang Song, Jiaming Song, Shengjia Zhao, Aditya Grover, Stefano Ermon.
+ **WMVL**: A Wasserstein Minimum Velocity Approach to Learning Unnormalized Models. Ziyu Wang, Shuyu Cheng, Yueru Li, Jun Zhu, Bo Zhang. [[paper]](http://proceedings.mlr.press/v108/wang20j.html) [[Code (TF)]](https://github.com/thu-ml/wmvl)
#### CVPR 2020
+ Flow Contrastive Estimation of Energy-Based Models. Ruiqi Gao, Erik Nijkamp, Diederik P. Kingma, Zhen Xu, Andrew M. Dai, Ying Nian Wu.
+ Joint Training of Variational Auto-Encoder and Latent Energy-Based Model. Tian Han, Erik Nijkamp, Linqi Zhou, Bo Pang, Song-Chun Zhu, Ying Nian Wu.

#### AAAI 2020
+ On the Anatomy of MCMC-Based Maximum Likelihood Learning of Energy-Based Models. Erik Nijkamp, Mitch Hill, Tian Han, Ying Nian Wu, Song-Chun Zhu.

#### ICLR 2020
+ Meta-Learning Deep Energy-Based Memory Models. Sergey Bartunov, Jack Rae, Simon Osindero, Timothy Lillicrap.
+ Residual Energy-Based Models for Text Generation. Yuntian Deng, Anton Bakhtin, Myle Ott, Arthur Szlam, Marc'Aurelio Ranzato.
+ Energy-based models for atomic-resolution protein conformations. Yilun Du, Joshua Meier, Jerry Ma, Rob Fergus, Alexander Rives.

#### ICML 2020
+ Training Deep Energy-Based Models with f-Divergence Minimization. Lantao Yu, Yang Song, Jiaming Song, Stefano Ermon.
+ From Sets to Multisets: Provable Variational Inference for Probabilistic Integer Submodular Models. Aytunc Sahin, Yatao Bian, Joachim Buhmann, Andreas Krause.

#### Before 2020
+ Generative Modeling by Estimating Gradients of the Data Distribution. Yang Song, Stefano Ermon. NeurIPS 2019 (oral).
+ Learning deep kernels for exponential family densities. Li Wenliang, Danica J. Sutherland, Heiko Strathmann, Arthur Gretton. ICML 2019.
+ Optimal Continuous DR-Submodular Maximization and Applications to Provable Mean Field Inference. Yatao Bian, Joachim Buhmann, Andreas Krause. ICML 2019.
+ Implicit Generation and Modeling with Energy Based Models. Yilun Du, Igor Mordatch. NeurIPS 2019.
+ Learning Non-Convergent Non-Persistent Short-Run MCMC Toward Energy-Based Model. Erik Nijkamp, Mitch Hill, Song-Chun Zhu, Ying Nian Wu. NeurIPS 2019.
+ **ADE**: Exponential Family Estimation via Adversarial Dynamics Embedding. Bo Dai, Zhen Liu, Hanjun Dai, Niao He, Arthur Gretton, Le Song, Dale Schuurmans. NeurIPS 2019. [[paper]](https://arxiv.org/abs/1904.12083) [[Code (TF)]](https://github.com/lzzcd001/ade-code)
+ Concept Learning with Energy-Based Models. Igor Mordatch. arXiv 1811.
+ Cooperative Training of Descriptor and Generator Networks. Jianwen Xie, Yang Lu, Ruiqi Gao, Song-Chun Zhu, Ying Nian Wu. arXiv 1609.
+ Learning Generative ConvNets via Multi-grid Modeling and Sampling. Ruiqi Gao, Yang Lu, Junpei Zhou, Song-Chun Zhu, Ying Nian Wu. CVPR 2018.
+ Inference in Probabilistic Graphical Models by Graph Neural Networks. KiJung Yoon, Renjie Liao, Yuwen Xiong, Lisa Zhang, Ethan Fetaya, Raquel Urtasun, Richard Zemel, Xaq Pitkow. ICML 2019 (workshop).
+ Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor. Tuomas Haarnoja, Aurick Zhou, Pieter Abbeel, Sergey Levine. ICML 2018.
+ Conditional Noise-Contrastive Estimation of Unnormalised Models. Ciwan Ceylan, Michael U. Gutmann. ICML 2018.
+ Adversarial Contrastive Estimation. Avishek Joey Bose, Huan Ling, Yanshuai Cao. ACL 2018.
+ Equilibrium Propagation: Bridging the Gap between Energy-Based Models and Backpropagation. Benjamin Scellier, Yoshua Bengio. Front. Comput. Neurosci. 2017.
+ Reinforcement Learning with Deep Energy-Based Policies. Tuomas Haarnoja, Haoran Tang, Pieter Abbeel, Sergey Levine. ICML 2017.

Note: More papers much earlier are not calculated. May try to add some later.
