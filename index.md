
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

    <!-- MathJax Script -->
    <script type="text/javascript" async
            src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
    </script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.13/katex.min.css">
    <script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.13/katex.min.js"></script>

    <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    
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
            background-color: #fff;
            padding: 0.5em 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
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
            margin-top: 50px; 
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
            background-color: #fff;
            color: #333;
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

        #projects {
            /* Add any styling for the projects section here */
        }

        .video-container {
            position: relative;
            width: 100%;
            padding-bottom: 56.25%; /* 16:9 aspect ratio (9 / 16 * 100) */
        }

        .video-container iframe {
             position: absolute;
             top: 0;
             left: 0;
             width: 100%;
             height: 100%;
             border: 1px solid black; /* You can add a border or other styling if desired */
        }

        .pdf-container {
            width: 100%; /* Adjust the width as needed */
            height: 100%; /* Adjust the width as needed */
        }

        .pdf-container embed {
            width: 100%;
            height: 100%;
        }

        .equation-container {
            white-space: nowrap; /* Prevent line breaks */
            overflow-x: auto; /* Allow horizontal scrolling if needed */
            overflow-wrap: break-word; /* Enable word wrapping */
            width: 100%; /* Adjust width as needed */
            margin: 20px 0; /* Add margin for better readability */
        }
        
    </style>
</head>
<body>

<header>
</header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#publications">Publications</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>
            My name is Mohsen. I have been working with Dr. Andreas Adelmann at the <a href="https://www.psi.ch/en">Paul Scherrer Institute</a>, Switzerland, since July of 2023 as a postdoc. Here, my main task is upgrading <a href="https://gitlab.psi.ch/OPAL">OPAL</a>  (Object Oriented Particle Accelerator Library) with an exa-scalable and portable particle-in-cell library called <a href="https://github.com/IPPL-framework">IPPL</a>  (Independent Parallel Particle Layer) for simulating particle accelerators, plasma, and rarefied gas dynamics.
        </p>
        
        <p>
            In Dec. 2021, I joined <a href="https://www.mit.edu">MIT</a>, USA, and worked with Prof. Nicolas Hadjiconstantinou on developing a general-purpose variance reduction for Monte Carlo methods in kinetic theory. 
        </p>

        <p>
            Before that, I worked with Prof. Laurent Villard at the <a href="https://www.epfl.ch/research/domains/swiss-plasma-center/">Swiss Plasma Center</a>, Switzerland, as a postdoc on a particle-in-cell code for simulating plasma in confined geometry called <a href="https://www.epfl.ch/research/domains/swiss-plasma-center/research/theory/codes/research_theory_codes_orb5/">ORB5</a>. 
        </p>
        
        <p>
           I carried out my doctoral studies at RWTH Aachen University, Germany, under the supervision of Prof. Manuel Torrilhon and Dr. Hossein Gorji. My research topic was developing efficient Monte Carlo methods for simulating dense gas, liquid, and phase transition in kinetic theory. 
        </p>
        
    </section>

<section id="projects">
    <h2>Projects</h2>

    
    <h3>Phase Transition of Argon [<a href="#FPmultiphase">1</a>]</h3>
    <h4>a) Coalescence of Nano Droplets</h4>
    <p>Formation and coalescence of nano droplets in spinodal decomposition of Argon shown by the evolution of number density at initial temperature $120\ \mathrm{K}$ and number density of $3\times 10^{27}$ and $5\times 10^{27}\ \mathrm{m}^{-3}$. 
 </p>

<div class="video-container">
    <iframe src="spinodal_1.mp4" frameborder="0" allowfullscreen></iframe>
</div>

<p>  </p>

<div class="video-container">
 <iframe src="spinodal_2.mp4" frameborder="0" allowfullscreen></iframe>
</div>

 <h4>b) Formation of Bubbles</h4>
    
<p> Evolution of  number density for spinodal decomposition of Argon at initial temperature $120\ \mathrm{K}$ and number density of $8\times 10^{27}\ \mathrm{m}^{-3}$. </p>

<div class="video-container">
<iframe src="spinodal_3.mp4" frameborder="0" allowfullscreen></iframe>
</div>

<h4>c) Spinodal Decomposition in 3D</h4>
    
<p> 3D simulation of spinodal decomposition  at the initial temperature $120\ \mathrm{K}$ and number density $8\times 10^{27}\ \mathrm{m}^{-3}$. </p>

<div class="video-container">
    <iframe src="spinodal_4.mp4" frameborder="0" allowfullscreen></iframe>
</div>

    <h3>Variance reduction</h3>

<p>One of the main challenges in interpreting solution to statistical models is noise (or variance) in prediction. We develope a general-pupose varince reduction method for sotchastic processes where the target pdf is around an equilibrium/control-variate denisty. Using the equilibrium distribution function $f^\mathrm{eq}( v| x, t)$ as the control variate, one can formulate any velocity moment of target distribution $R( v)$ using importance sampling via

<div class="equation-container">
        \[ \int R(v) f(v|x,t) \, d^3 v = \int R(v) \left(1-w(v|x,t)\right) f(v|x,t) \, d^3 v + \int R(v) f^\mathrm{eq}(v|x,t) \, d^3 v \]
</div>
    
\begin{equation}
\sloppy \int R( v) f( v| x,t) d^3  v 
= \int R(v) \left(1-w(v| x,t)\right) f( v| x,t) d^3 v + \int R( v) f^\mathrm{eq}( v| x,t) d^3 v,
\end{equation}
where
\begin{equation}
w( v| x,t) = \frac{f^\mathrm{eq}(v|x, t)}{f(v|x, t)}~.
\label{eq:weight_def}
\end{equation}
Here $R(v)$ denotes a velocity polynomial, e.g. $R(v) \in \{1,v_i,v_iv_j...\}$ for $i,j=1,2,3$. </p>


<p> In this project, we design a consistent and least-biased evolution equation for the weight $w$ for a given Boltzmann collision operator as well as a general Fokker-Planck type equation. The following figures show the snapshot estimate of number density, bulk velocity, and temperature for the Sod-Shock tube test case. We also show how the noise varies with respect to the signal for the standard Monte Carlo and the introduced variance reduction method. </p>

<img src="n_nv10_shock3.pdf" alt="Description of the image" width="300" height="300">

<img src="U_nv10_shock3.pdf" alt="Description of the image" width="300" height="300">

<img src="T_nv10_shock3.pdf" alt="Description of the image" width="300" height="300">

<img src="var_shock.pdf" alt="Description of the image" width="300" height="300">

    <h3>Density Estimation</h3>
    
</section>

<section id="experiance">
    <h2>Experience</h2>
    <h3>Postdoc at <a href="https://www.psi.ch/en">Paul Scherrer Institute</a></h3>
    <p>Scientific Computing, Theory and Data</p>
    <p>Switzerland, Jul. 2023 - present.</p>
    
    <h3>Postdoc at <a href="https://www.mit.edu">Massachusetts Institute of Technology</a> </h3>
    <p>Department of Mechanical Engineering</p>
    <p>USA, Dec. 2021 - Jun. 2023.</p>

    <h3>Postdoc at <a href="https://www.epfl.ch/en/">EPFL</a> </h3>
    <p><a href="https://www.epfl.ch/research/domains/swiss-plasma-center/">Swiss Plasma Center</a></p>
    <p>Switzerland, Oct. 2020 - Nov. 2021.</p>
</section>

<section id="education">
    <h2>Education</h2>
    <h3>Ph.D. in Applied and Computational Mathematics</h3>
    <p>RWTH Aachen University, Germany, 2020.</p>
    
    <h3>Master's in Simulation Sciences</h3>
    <p>RWTH Aachen University, Germany, 2017.</p>
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
        
        <li id="FPmultiphase">
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
            &bull; Mohsen Sadr, Qian Wang, and M. Hossein Gorji. "Coupling kinetic and continuum using data-driven maximum entropy distribution" <em>Journal of Computational Physics</em>, 444, 110542, 2021 [<a href="https://doi.org/10.1016/j.jcp.2021.110542">Elsevier</a> | <a href="https://arxiv.org/abs/2308.05672">Preprint</a>].
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
