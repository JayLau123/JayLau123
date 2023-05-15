### Hi there 👋  

:microscope: My research interests span physics, chemistry, materials science, computational science and engineering, etc. Especially molecular and materials design, characterization, and optimization, with more emphasis on **AI4Science** (The fourth paradigm and four parts: computer-aided, data-driven, statistics-based, physics-informed method), and other exciting ways of exploiting scientific computation to understand the world.

🚀 I seek to provide useful computing techniques to support break new grounds in these interdisciplinary fields to addresses questions with broad societal impact. Here are some of my most interested topics:

:heavy_check_mark: Can we aid the design process of molecules, materials, and devices by leveraging on DFT and machine learning? To achieve the best balance of accuracy and efficiency, practicality and interpretability?

:heavy_check_mark: Can we be able to design materials with particular chemical compositions and crystal structure at the atomic level given a set of desired properties or functions, based on computational/data-driven approaches?

:heavy_check_mark: Can we move to larger systems, longer time scales, higher data efficiency, better generalization and transferability, and eventually more accurate and realistic applications in molecule and materials science with DFT+GNN?

**🎉 My Google Scholar**

I'm thankful for the wonderful collaborations that have led to the publications here.

https://scholar.google.com/citations?user=f2qAmGIAAAAJ&hl=en

📧 I really appreciate prospective collaborators reaching out, especially on physice-based machine learning, qunatum chemistry, and HPC for materials research and quantum computing. Please feel free to drop me an email: jayfree2023@outlook.com

**🛠️ I'm also interested in collecting some useful AI tools to improve productivity, they are my brainstorming partner and positive assistants with can-do attitude!**

https://github.com/JayLau123/GPT-toolkit-summary

### 👨‍💻 Current project: GNN-aided characterization for molecules.

Probably approximately correct function(PAC) explains how to find the best candidate structure $x$ with a high probability, which suits for loss function in our model.
 
$$p(|f(x)-y| \leq \epsilon) \geq 1-\delta$$

$x$ is the candidate structure, $y$ is the observed properties $P$ from Raman spectrum, which is the true label. If the prediction is very accurate, then $|f(x)-P|\leq \epsilon$. We can calculate the spectrum properties with known atoms and their structure based on quantum chemistry. Let's denote it as $\boldsymbol{f}$. We hope to find the best candidate structure $x$ with a high probability: $p(|f(x)-P| \leq \epsilon) \geq 1-\delta$. However, regardless of the difficulties to choose exchange-correlation functional $E_{XC}$ in solving Kohn-Sham equation(KS), the $\boldsymbol{f}$ can be very computational-expensive. Alternatively, can we use current database from PubChem, NIST, Wiley’s library, etc. to train a convolutional neural network to predict spectrum, so that given a molecular structure (graph-based representation), it will output the spectrum automatically? We are going to build such a network named forward model $\boldsymbol{f}$.

[![trophy](https://github-profile-trophy.vercel.app/?username=JayLau123&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=JayLau123)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JayLau123&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

