## Hi there  :v:

🦫 I'm a Research Associate in Prof. Sam Peng's research group with research interests span physics, materials, and machine learning. 

---

### Scientific research paradigms

#### First paradigm （Empirical Science）

:mag_right: Observation and Empiricism. The foundation of scientific discovery lies in observing, recording, and describing natural phenomena. From these observations, scientists formulate hypotheses, test them, and develop laws that explain the behavior of the natural world. This paradigm is characterized by the empirical method of scientific inquiry, where hypotheses are validated through experimentation.

Key Examples: Galileo's motion experiments, Newton's laws of motion, and Mendel's pea plant experiments. These foundational studies exemplify the hypothetical-deductive method, where observations lead to testable hypotheses, and the results further solidify scientific laws.


#### Second paradigm (Theoretical Science)

:bulb: Mathematical and Analytical Models. Theoretical science advances knowledge by building on mathematical analysis and abstract reasoning, often extending beyond direct empirical evidence. The goal is to derive theories that can explain observed phenomena and predict new ones. This paradigm emphasizes using limited experimental data, or even purely thought experiments, to recover the underlying mathematical structure of physical laws.

Key Examples: Maxwell's equations, Einstein's theory of general relativity, and the development of quantum mechanics. These theories stem from rigorous mathematical frameworks that can explain and predict the physical behavior of systems from atomic to cosmic scales.


#### Third paradigm (Computational Science)

:computer: Simulated Reality and Numerical Modeling. The computational paradigm represents a shift towards creating virtual models of the real world. By translating physical systems into mathematical equations and solving them using computational techniques, scientists can simulate phenomena that are difficult or impossible to observe directly. These simulations rely on verified physical equations, empirical data, and high-performance computing.

Key Examples: Simulated nuclear tests, computational materials science, and climate modeling. These examples demonstrate how computational tools allow for the exploration and understanding of complex systems, where direct experimentation may be limited by scale, safety, or practicality.


#### Fourth paradigm (AI for Science)

:collision: Computer-aided, Data-driven, Statistics-based, Physics-informed Discovery and Interdisciplinary Integration. The latest paradigm in scientific research is the integration of artificial intelligence (AI), machine learning (ML), and high-performance computing (HPC) with traditional scientific methods. This interdisciplinary approach leverages data-driven models to augment and accelerate discovery. AI models can identify patterns in massive datasets, predict outcomes, and propose hypotheses that can then be validated through scientific methods and grounded in physics-informed theories.

Key Examples: Alpha-Fold, drug discovery, symbolic regression for uncovering new physical laws, and the use of neural networks in discovering complex material properties. This paradigm enables researchers to harness vast computational power, advancing science through AI-assisted predictions and insights.

As highlighted in **"Scientific Discovery in the Age of Artificial Intelligence"** ([Nature, 2023](https://www.nature.com/articles/s41586-023-06221-2)), AI plays an increasingly critical role in modern science. The fusion of AI with traditional scientific inquiry forms a comprehensive methodology that is both powerful and transformative, pushing the boundaries of what is discoverable.

For a deeper exploration of this paradigm, the landmark publication The Fourth Paradigm by Microsoft Research (Microsoft Research, 2009) underscores the challenges and opportunities of applying AI and machine learning to scientific research, particularly in using symbolic regression to discover new physical laws: https://www.microsoft.com/en-us/research/wp-content/uploads/2009/10/Fourth_Paradigm.pdf

---

### Explore the overlaps of physics and ML

My methodological interest in this field lies in advancing multi-methods materials designs and the application of experimental and statistical analysis to DFT and machine learning. It is all about harnessing the power and beauty of physical laws and data. 

Machine learning (ML) has shown great promise in advancing our understanding of various aspects of physics. By leveraging ML techniques, researchers can analyze large and complex datasets, identify patterns, and make predictions more efficiently than traditional computational methods. Here are some ways to use machine learning to investigate physics:

1. Data analysis and pattern recognition: Machine learning can help analyze large datasets generated from experiments or simulations in physics, identifying patterns and relationships that may be difficult to discern through manual analysis. Examples include detecting anomalies in particle collider data or identifying features in astronomical images.

2. Surrogate modeling: ML models can be trained to approximate complex physical models, reducing the computational cost of simulations. These surrogate models can be used to predict outcomes of physical systems more efficiently than traditional methods, enabling faster exploration of parameter spaces and optimization of system properties.

3. Model improvement and parameter estimation: Machine learning can be used to refine existing physical models by identifying discrepancies between model predictions and experimental data. ML can also assist in estimating model parameters or initial conditions, which can be challenging in complex systems with many degrees of freedom.

4. Inverse problems: Machine learning can be applied to solve inverse problems in physics, where the goal is to determine the underlying cause of an observed effect. Examples include determining the distribution of mass in a galaxy from gravitational lensing data or inferring material properties from scattering data in materials science.

5. Discovery of new physical laws: ML algorithms can be used to discover new laws and relationships in physics by analyzing data and identifying underlying patterns or correlations. For example, symbolic regression techniques can be employed to find functional forms that best describe the relationship between variables in a physical system.

6. Quantum computing and quantum information: ML techniques can be used to study quantum systems, such as optimizing quantum gate operations, designing error-correcting codes, or simulating quantum systems more efficiently.

To get started with using machine learning to investigate physics, follow these steps:

1. Identify a problem or area of interest in physics that could benefit from machine learning techniques.
2. Acquire a suitable dataset, either from experiments, simulations, or publicly available sources.
3. Familiarize yourself with machine learning tools and libraries, such as TensorFlow, PyTorch, or scikit-learn, and choose the most appropriate ML algorithm for your problem.
4. Preprocess and clean the data, ensuring it is properly formatted and suitable for training your ML model.
5. Train and validate your ML model, fine-tuning hyperparameters to achieve optimal performance.
6. Analyze and interpret the results, comparing your model's predictions with experimental or simulation data and assessing the model's performance.


---

## My Current Project


👨‍💻 Currently, we delve deep into the fascinating realm of metallic chemical elements lanthanide: $[\mathrm{Xe}] 4 \mathrm{f}^N$, where $N$ runs from $1\left(\mathrm{Ce}^{3+}\right)$ to $13\left(\mathrm{Yb}^{3+}\right)$ along the series of $\mathrm{Ln^{3+}}$, and the lanthanide-doped nanocrystal ($\beta-\mathrm{NaYF_4}:\mathrm{Yb}^{3+}/\mathrm{Tm}^{3+}/\mathrm{Er}^{3+}$, known as upconversion nanoparticles UCNPs). 

:atom: Depart from lanthanides' abundant electronic structure in solid, we try to explore microscopic interactions(electron, photon, phonon, etc) and energy transfer mechanisms (ED, MD, MPR, up-conversion, cross-relaxation, etc) with Judd-Ofelt theory and DFT. Grounded in an extensive theoretical framework and calculated transition rates, we implement Monte Carlo model and machine learning algorithm to simulate the probabilistic, collective energy transfer behaviour among hundreds to millions of ions within single nanoparticles with diameters ranging from 4 $nm$ to 50 $nm$. 

🚀 The overarching goal of these endeavors is to hack the energy transfer network to design custom-based nanomaterials: UCNP, perfect for their ultimate application: serving as long-term, multi-color optical probes in single-molecule tracking and imaging. Let’s push the boundaries of UCNPs research, illuminating paths for future innovations in spectroscopy and bio-imaging, and drive innovation together!


**I seek to hack the energy transfer networks, build a useful computational model to provide insights and predictive support for the development of UCNPs. Here are some of my current most interested topics:**

:heavy_check_mark: How many term symbols $\mathrm{{ }^{2 S+1} L_J}$ should be involved for $\mathrm{Yb}^{3+}, \mathrm{Tm}^{3+}, \mathrm{Er}^{3+}$ in $\beta-\mathrm{NaYF_4}$, and quantitatively describe the energy level's value, shifting, and broadening under crystal-field and external electromagnetic field?

:heavy_check_mark: How do we specify the existence of various energy transfer pathways in UCNP based on experimental observation and theoretical investigation beyond known categories such as electric-dipole induced radiative transition(ED), magnetic-dipole induced radiative transition(MD), multipolar interaction, multi-phonon relaxation, non-resonant donor-acceptor energy transfer process(ET)? 

:heavy_check_mark: How do we obtain the overlap integral $\mathrm{S_0}$ experimently or computationally, and how many phonons could be involved in non-resonant energy transfer processes due to energy mismatching between donor and acceptor?

:heavy_check_mark: What's the distinctions between MC and ODE? e.g. MC generates more blink curves than smooth population evolution curves generated by ODE; is this normal? How to handle with the interionic distance $r_0$ required by ET process in ODE? 

:heavy_check_mark: Doping percentages and MC model stochasticity: how do they relate? If large particles or high doping that result in more doped ions produce a more accurate simulation than small particles and low doping?

:heavy_check_mark: Should we take into account the local site symmetry responsible for the selection rules at different lattice sites, as viewed from the perspective of a single ion? If not, is the selection rule applicable to every ion in the lattice environment?

:heavy_check_mark: How many adjustable variables cound be optimizaed (lanthanides categories and percentages, crystal structure, particle size, laser power density and polarization, etc) that supprot precise tuning of the photonphysical properties and high energy transfer efficiency of UCNP?

:heavy_check_mark: Could we explore the potential of correlating the Monte-Carlo model with neural networks due to their structural and dynamics similarities?


**🛠️ I'm also interested in collecting some useful AI tools to improve productivity, they are my brainstorming partner and positive assistants with can-do attitude!**

https://github.com/JayLau123/GPT-toolkit-summary
