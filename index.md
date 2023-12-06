
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohsen Sadr - Welcome</title>
    <!-- MathJax Configuration -->
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
                inlineMath: [['$', '$'], ['\\(', '\\)']],
                displayMath: [['$$', '$$'], ['\\[', '\\]']],
                processEscapes: true
            }
        });
    </script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-image: url('IMG_0006.jpg'); /* Replace 'path/to/your/image.jpg' with the actual path to your image */
            background-size: contains; /* Adjust the background-size property as needed */
            background-position: center;
            background-repeat: no-repeat;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            height: 50vh;
        }

        nav {
            background-color: #f4f4f4;
            padding: 0.5em 0;
            text-align: center;
        }

        nav a {
            color: #333;
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 0.5em;
            border-radius: 4px;
            transition: background-color 0.3s;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #555;
        }

        section {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        p {
            color: #555;
            margin-bottom: 1em;
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: #fff;
        }

        section#publications {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section#publications h2 {
            color: #333;
        }

        section#publications ul {
            list-style-type: none;
            padding: 0;
        }

        section#publications li {
            margin-bottom: 1em;
        }
    </style>
</head>
<body>

<header>
</header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#contact">Contact</a>
        <a href="#publications">Publications</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>
            My name is Mohsen. I have been working with Dr. Andreas Adelmann at the <a href="https://www.psi.ch/en">Paul Scherrer Institute</a>, Switzerland, since July of 2023 as a postdoc. Here, my main task is upgrading <a href="https://gitlab.psi.ch/OPAL">OPAL</a>  (Object Oriented Particle Accelerator Library) with an exa-scalable and portable particle-in-cell library called <a href="https://github.com/IPPL-framework">IPPL</a>  (Independent Parallel Particle Layer) for simulating particle accelerators, plasma, and rarefied gas dynamics.
        </p>
        
        <p>
            In Dec. 2021, I joined MIT, USA, and worked with Prof. Nicolas Hadjiconstantinou on developing a general-purpose variance reduction for Monte Carlo methods in kinetic theory. 
        </p>

        <p>
            Before that, I worked with Prof. Laurent Villard at the Swiss Plasma Center, Switzerland, as a postdoc on a particle-in-cell code for simulating plasma in confined geometry called <a href="https://www.epfl.ch/research/domains/swiss-plasma-center/research/theory/codes/research_theory_codes_orb5/">ORB5</a>. 
        </p>
        
        <p>
           I carried out my doctoral studies at RWTH Aachen University, Germany, under the supervision of Prof. Manuel Torrilhon and Dr. Hossein Gorji. My research topic was developing efficient Monte Carlo methods for simulating dense gas, liquid, and phase transition in kinetic theory. 
        </p>
        
    </section>

<section id="education">
    <h2>Education</h2>
    <h3>Ph.D. in Applied and Computational Mathematics</h3>
    <p>RWTH Aachen University, Germany, 2020.</p>
    
    <h3>Master's in Simulation Sciences</h3>
    <p>RWTH Aachen University, Germany, 2017.</p>
</section>

<section id="projects">
    <h2>Projects</h2>
    <h3>Phase Transition</h3>
    <h4>Coalescence of Nano Droplets</h4>
    <p>Formation and coalescence of nano droplets in spinodal decomposition using the DFP-SP model. The evolution of number density is shown for argon in the physical domain $\Omega_x=[0,L]^2\times[0,1]\ \mathrm{m}^3$, where $L=5\times10^{-8}\ \mathrm{m}$, using $N_p=1.33 \times 10^{8}$ particles.  Initial temperature and number density are $T^{(0)}=120\ \mathrm{K}$ and $n^{(0)}=3\times 10^{27}\ \mathrm{m}^{-3}$, respectively. 
 </p>
    
    <iframe width="630" height="315" src="spinodal_1.webm" frameborder="0" allowfullscreen></iframe>

 <p> Formation and coalescence of nano droplets in spinodal decomposition using the DFP-SP model. The evolution of number density is shown for argon in the physical domain $\Omega_x=[0,L]^2\times[0,1]\ \mathrm{m}^3$ where $L=5\times10^{-8}\ \mathrm{m}$, using $N_p=1.25 \times 10^{8}$ particles. Initial temperature and number density are $T^{(0)}=120\ \mathrm{K}$ and $n^{(0)}=5\times 10^{27}\ \mathrm{m}^{-3}$ respectively. Formation  of droplets larger than Movie 1 can be observed here.  </p>

 <iframe width="630" height="315" src="spinodal_2.mp4" frameborder="0" allowfullscreen></iframe>

 <h4>Formation of Bubbles</h4>
    
<p> Evolution of  number density for spinodal decomposition of argon obtained from the DFP-SP model inside the domain $\Omega_x=[0,L]^2\times[0,1]\ \mathrm{m}^3$ where $L=5\times10^{-8}\ \mathrm{m}$ with initial temperature and number density $T^{(0)}=120\ \mathrm{K}$ and $n^{(0)}=8\times 10^{27}\ \mathrm{m}^{-3}$ respectively, using $N_p=1.33 \times 10^{8}$ particles. Formation of bubbles is obtained. </p>


<iframe width="630" height="315" src="spinodal_3.mp4" frameborder="0" allowfullscreen></iframe>

<h4>Spinodal Decomposition in 3D</h4>
    
<p> Three dimensional spinodal decomposition using the DFP-SP model. Evolution of number density of argon in the physical domain $\Omega_x=[0,L]^3\ \mathrm{m}^3$ where $L=5\times10^{-8}\ \mathrm{m}$ is obtained. Initial temperature $T^{(0)}=120\ \mathrm{K}$, initial number density $n^{(0)}=8\times 10^{27}\ \mathrm{m}^{-3}$ and number of particles $N_p=4.32\times10^8$ are employed. </p>

    <iframe width="630" height="315" src="spinodal_4.mp4" frameborder="0" allowfullscreen></iframe>
    
</section>

<section id="publications">
    <h2>Publications</h2>
    <ul>
        <strong>Variance Reduction:</strong>
        
        <li>
            &bull; Mohsen Sadr, and Nicolas G. Hadjiconstantinou. "A variance-reduced direct Monte Carlo simulation method for solving the Boltzmann equation over a wide range of rarefaction" <em>Journal of Computational Physics</em>, 472, 111677, 2023 [<a href="https://doi.org/10.1016/j.jcp.2022.111677">Elsevier</a> | <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4148310">Preprint</a>].
        </li>

        <li>
            &bull; Mohsen Sadr, and Nicolas G. Hadjiconstantinou. "Variance reduced particle solution of the Fokker-Planck equation with application to rarefied gas and plasma dynamics" <em>Journal of Computational Physics</em>, 492, 112402, 2023 [<a href="https://doi.org/10.1016/j.jcp.2023.112402">Elsevier</a> | <a href="https://dx.doi.org/10.2139/ssrn.4353547">Preprint</a>].
        </li>
        
        <strong>Modelling Phase Transition:</strong>
        
        <li>
            &bull; Mohsen Sadr, Marcel Pfeiffer, and M. Hossein Gorji. "Fokker-Planck-Poisson kinetics: multi-phase flow beyond equilibrium" <em>Journal of Fluid Mechanics</em>, 920, A46, 2021 [<a href="https://doi.org/10.1017/jfm.2021.461">Cambridge University Press</a> | <a href="https://arxiv.org/abs/2308.05580">Preprint</a>].
        </li>

        <li>
            &bull; Mohsen Sadr, and M. Hossein Gorji. "Treatment of long-range interactions arising in the Enskog–Vlasov description of dense fluids" <em>Journal of Computational Physics</em>, 378, 129-142, 2019 [<a href="https://doi.org/10.1016/j.jcp.2018.11.005">Elsevier</a> | <a href="https://arxiv.org/abs/2308.05845">Preprint</a>].
        </li>

        <li>
            &bull; Mohsen Sadr, and M. Hossein Gorji. "A continuous stochastic model for non-equilibrium dense gases" <em>Journal of Physics of Fluids</em>, 29, 122007, 2017 [<a href="https://doi.org/10.1063/1.5004409">American Institute of Physics</a> | <a href="https://arxiv.org/abs/2308.05117">Preprint</a>].
        </li>

        <strong>Density Estimation:</strong>

        <li>
            &bull; Tony Tohme, Mohsen Sadr, Kamal Youcef-Toumi, and Nicolas G. Hadjiconstantinou. "MESSY Estimation: Maximum-Entropy based Stochastic and Symbolic densitY Estimation" <em>Transactions on Machine Learning Research (in review)</em>, 2023 [<a href="https://arxiv.org/abs/2306.04120">Preprint</a>].
        </li>

        <li>
            &bull; Mohsen Sadr, Nicolas G. Hadjiconstantinou, and M. Hossein Gorji. "Wasserstein-penalized Entropy closure: A use case for stochastic particle methods" <em>Journal of Computational Physics (in review)</em>, 2023 [<a href="https://arxiv.org/abs/2306.04120">Preprint</a>].
        </li>

        <li>
            &bull; Mohsen Sadr,  Manuel Torrilhon, and M. Hossein Gorji. "Gaussian Process Regression for Maximum Entropy Distribution" <em>Journal of Computational Physics</em>, 418, 109644, 2020 [<a href="https://doi.org/10.1016/j.jcp.2020.109644">Elsevier</a> | <a href="https://arxiv.org/abs/2308.06149">Preprint</a>].
        </li>

        <strong>Approximating Collision Operator:</strong>

        <li>
            &bull; Fabian Mies, Mohsen Sadr, and Manuel Torrilhon. "An efficient jump-diffusion approximation of the Boltzmann equation" <em>Journal of Computational Physics</em>, 490, 112308, 2023 [<a href="https://doi.org/10.1016/j.jcp.2023.112308">Elsevier</a> | <a href="https://arxiv.org/abs/2112.08362">Preprint</a>].
        </li>

        <li>
            &bull; Fabian Mies, Mohsen Sadr, and Manuel Torrilhon. "Coupling kinetic and continuum using data-driven maximum entropy distribution" <em>Journal of Computational Physics</em>, 444, 110542, 2021 [<a href="https://doi.org/10.1016/j.jcp.2021.110542">Elsevier</a> | <a href="[https://arxiv.org/abs/2112.08362](https://arxiv.org/abs/2308.05672)">Preprint</a>].
        </li>

        <strong>Simulation of Plasma/Fluid:</strong>
        
        <li>
        &bull; Mohsen Sadr, Alexey Mishchenko, Thomas Hayward-Schneider, Axel Koenies, Alberto Bottino, Alessandro Biancalani, Peter Donnel, Emmanuel Lanti, and Laurent Villard. "Linear and nonlinear excitation of TAE modes by external electromagnetic perturbations using ORB5" <em>Plasma Physics and Controlled Fusion</em>, 64, 085010, 2022 [<a href="https://iopscience.iop.org/article/10.1088/1361-6587/ac73eb">IOP Publishing Ltd (open access)</a>].
        </li>

        <li>
        &bull; P Donnel, J Cazabonne, L Villard, S Brunner, S Coda, J Decker, M Murugappan, and M Sadr. "Quasilinear treatment of wave–particle interactions in the electron cyclotron range and its implementation in a gyrokinetic code" <em>Plasma Physics and Controlled Fusion</em>, 63, 064001, 2021 [<a href="https://iopscience.iop.org/article/10.1088/1361-6587/abf53f">IOP Publishing Ltd (open access)</a>].
        </li>
        
        <li>
        &bull; Sima Farazi, Mohsen Sadr, Seongwon Kang, Martin Schiemann, Nikita Vorobiev, Viktor Scherer, Heinz Pitsch. "Resolved simulations of single char particle combustion in a laminar flow field" <em>Fuel</em>, 201, 15-28, 2017 [<a href="https://doi.org/10.1016/j.fuel.2016.11.011">Elsevier</a>].
        </li>
        
        
    </ul>
</section>

    <section id="contact">
        <h2>Contact</h2>
        <p>
            You can reach me at <a href="mailto:mohsen.sadr@psi.ch">mohsen.sadr@psi.ch</a> or <a href="mailto:mohsen.sadr91@gmail.com">mohsen.sadr91@gmail.com</a>.
        </p>
    </section>

    <footer>
        &copy; 2023 Mohsen Sadr. All rights reserved.
    </footer>

</body>
</html>
