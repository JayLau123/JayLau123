### Hi there 👋  

:microscope: My research interests span physics, chemistry, materials science, computational science and engineering, etc. Especially molecular and materials design, characterization, and optimization, with more emphasis on **AI4Science** (computer-aided, data-driven, statistics-based, physics-informed method), and other exciting ways of exploiting scientific computation to understand the world.

🚀 I seek to provide useful computing techniques to support break new grounds in these interdisciplinary fields to addresses questions with broad societal impact. Here are some of my most interested topics:

:heavy_check_mark: Can we aid the design process of molecules, materials, and devices by leveraging on DFT and machine learning? While DFT is an interpretable and alternative tool for machine learning.

:heavy_check_mark: Can we be able to design materials with particular chemical compositions and crystal structure at the atomic level given a set of desired properties or functions, based on CNN(consistutes), GNN(structure), and other computational/data-driven approaches?

:heavy_check_mark: Can we use ultra-fast Raman spectroscopy and tip enhanced Raman spectroscopy, combined with graph neural network(GNN), to understand matter at atomic scale with ultimate spatial and temporal resolutions? 

🍻 I really appreciate prospective collaborators reaching out, especially on physice-based machine learning, qunatum chemistry, and HPC for materials research and quantum computing. 

📧 Please feel free to drop me an email: jayfree2023@outlook.com

**🎉 My Google Scholar**

I am thankful for the wonderful collaborations that have led to the publications here.

https://scholar.google.com/citations?user=f2qAmGIAAAAJ&hl=en

**🛠️ I'm also interested in collecting some useful AI tools to improve productivity. Beat them, or join them, and make them!**

https://github.com/JayLau123/GPT-toolkit-summary

### 👨‍💻 Current project: Machine learning-aided characterization for molecules based on graph theory.

Probably approximately correct function(PAC) explains how to find the best candidate structure $x$ with a high probability, which suits for loss function in our model.
 
$$p(|f(x)-y| \leq \epsilon) \geq 1-\delta$$

$x$ is the candidate structure, $y$ is the observed properties $P$ from Raman spectrum, which is the true label. If the prediction is very accurate, then $|f(x)-P|\leq \epsilon$. We can calculate the spectrum properties with known atoms and their structure based on quantum chemistry. Let's denote it as $\boldsymbol{f}$. We hope to find the best candidate structure $x$ with a high probability: $p(|f(x)-P| \leq \epsilon) \geq 1-\delta$. However, regardless of the difficulties to choose exchange-correlation functional $E_{XC}$ in solving Kohn-Sham equation(KS), the $\boldsymbol{f}$ can be very computational-expensive. Alternatively, can we use current database from PubChem, NIST, Wiley’s library, etc. to train a convolutional neural network to predict spectrum, so that given a molecular structure (graph-based representation), it will output the spectrum automatically? We are going to build such a network named forward model $\boldsymbol{f}$.

________________________________________________________________________________________________________________________________________________________


[![trophy](https://github-profile-trophy.vercel.app/?username=JayLau123&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=JayLau123&show_icons=true&theme=radical)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JayLau123)](https://github.com/anuraghazra/github-readme-stats)

## How to use my GitHub efficiently

### Save your time, find everything you need efficiently. Good luck!

#### Please take a look of 'README.md', there are brief introductions to each file in each repository. It will guide you to find the file you need quickly. 

#### I'm not used to write formulas and equations in 'READ.md', instead, I prefer writing formula with LaTeX in jupyter notebook. You can download the files and find the LaTeX code of all the formulas in your own jupyter notebook!

#### There are some other useful learning materials in each repsoitory such as popular publications, reference books, course lectures from UChicago, etc.

## Quick start


### Python tutorials

Basic syntax, data structures, functions, etc.

https://thepythonguru.com/

https://www.codecademy.com/learn/learn-python-3

### Anaconda

Use Anaconda to install Python and new packages on your computer.

https://conda.io/projects/conda/en/latest/user-guide/getting-started.html

### Jupyter Notebook

Web-based interactive development environment for notebooks,code,and data.

https://docs.jupyter.org/en/latest/start/index.html



<!--
**JayLau123/JayLau123** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
