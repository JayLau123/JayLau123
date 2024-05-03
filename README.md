### Hi there  :v:

🦫 I'm a Research Associate in Prof. Sam Peng's research group with research interests span physics, materials, and computational science, etc. Currently, we delve deep into the fascinating realm of metallic chemical elements lanthanide ($[\mathrm{Xe}] 4 \mathrm{f}^N$, where $N$ runs from $1\left(\mathrm{Ce}^{3+}\right)$ to $13\left(\mathrm{Yb}^{3+}\right)$ along the series of $\mathrm{Ln^{3+}}$), and the lanthanide-doped nanocrystal ($\beta-\mathrm{NaYF_4}:\mathrm{Yb}^{3+}/\mathrm{Tm}^{3+}/\mathrm{Er}^{3+}$, known as upconversion nanoparticles UCNPs). 

:atom: Depart from lanthanides' abundant electronic structure in solid, we try to explore microscopic interactions(electron, photon, phonon, etc) and energy transfer mechanisms (ED, MD, MPR, up-conversion, cross-relaxation, etc) with Judd-Ofelt theory and DFT. Grounded in an extensive theoretical framework and calculated transition rates, we implement Monte Carlo model to simulate the probabilistic, collective energy transfer behaviour among hundreds to millions of ions within single nanoparticles with diameters ranging from 4 $nm$ to 50 $nm$. 

:microscope: The overarching goal of these endeavors is to design custom-based UCNPs, perfect for their ultimate application: serving as long-term, multi-color optical probes in single-molecule tracking and imaging. Let’s push the boundaries of UCNPs research, illuminating paths for future innovations in spectroscopy and bio-imaging, and drive innovation together!


**🚀 I seek to hack the energy transfer networks, build a useful computational model to provide insights and predictive support for the development of UCNPs. Here are some of my current most interested topics:**

:heavy_check_mark: How many term symbol $\mathrm{{ }^{2 S+1} L}$ should be involved for $\mathrm{Yb}^{3+}/, \mathrm{Tm}^{3+}/, \mathrm{Er}^{3+}$ in $\beta-\mathrm{NaYF_4}$, and quantitatively describe the energy level's value, shifting, and broadening under crystal-field and external electro-magnetic field?

:heavy_check_mark: How do we specify the existence of various energy transfer pathways in UCNP based on experimental observation and theoretical investigation beyond known categories such as electric-dipole induced transition(ED), magnetic-dipole induced transition(MD), multi-phonon relaxation, donor-acceptor energy transfer process(ET)? 

:heavy_check_mark: How do we obtain the overlap integral $\mathrm{S_0}$ experimently or computationally, and how many phonons could be involved in non-resonant energy transfer processes due to energy mismatching between donor and acceptor?

:heavy_check_mark: Shall we consider the local site symmetry that responsible for selection rule in different lattice site from single ion's perspective?

:heavy_check_mark: Can we relate the Monte-Carlo model to graph neural network(GNN) due to their structure similarity, and speed up and optimize the simulation significantly?


**🛠️ I'm also interested in collecting some useful AI tools to improve productivity, they are my brainstorming partner and positive assistants with can-do attitude!**

https://github.com/JayLau123/GPT-toolkit-summary

### 👨‍💻 Current project

Probably approximately correct function(PAC) explains how to find the best candidate structure $x$ with a high probability, which suits for loss function in our model.
 
$$p(|f(x)-y| \leq \epsilon) \geq 1-\delta$$

$x$ is the candidate structure, $y$ is the observed properties $P$ from Raman spectrum, which is the true label. If the prediction is very accurate, then $|f(x)-P|\leq \epsilon$. We can calculate the spectrum properties with known atoms and their structure based on quantum chemistry. Let's denote it as $\boldsymbol{f}$. We hope to find the best candidate structure $x$ with a high probability: $p(|f(x)-P| \leq \epsilon) \geq 1-\delta$. However, regardless of the difficulties to choose exchange-correlation functional $E_{XC}$ in solving Kohn-Sham equation(KS), the $\boldsymbol{f}$ can be very computational-expensive. Alternatively, can we use current database from Materials Project, NOMAD, NIST, etc, to train a graph neural network(GNN) to predict spectrum, so that given a molecular structure (graph-based representation), it can output the spectrum automatically? We are going to build such a network named forward model $\boldsymbol{f}$.


**🎉 My Google Scholar**

I'm thankful for the wonderful collaborations that have led to the publications here.

{https://scholar.google.com/citations?user=f2qAmGIAAAAJ&hl=en}(1)

📧 I really appreciate prospective collaborators reaching out, especially on lanthanide-doped luminescent nanocrystal. Please feel free to drop me an email: jayfree2023@outlook.com

