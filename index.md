
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
            padding-top: calc(var(--nav-height)); /* Dynamic adjustment */
        }

        nav {
            background-color: #fff;
            padding: 1em 0;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%; /* Full-width spanning the entire page */
            display: flex; /* Use flexbox for alignment */
            justify-content: center; /* Center the content horizontally */
            flex-wrap: wrap; /* Ensure items wrap to the next line if needed */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            z-index: 1000;
            transform: translateY(0); /* Initial position */
            transition: transform 0.3s ease-in-out; /* Smooth transition */
        }

        header {
            background-image: url('IMG_0006.jpg'); /* Replace 'IMG_0006.jpg' with the actual path to your image */
            background-size: contains; /* Adjusts the height of the background image to 50% of its container */
            background-position: center; /* Centers the image within the header */
            background-repeat: no-repeat; /* Prevents the image from repeating */
            color: #fff; /* Text color */
            text-align: center; /* Centers the text */
            padding: 1em 0; /* Padding for spacing */
            height: 50vh; /* Sets the header's height to 50% of the viewport height */
            margin-top: 90px;
        }
        
        nav a {
            color: #333;
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 0.5em;
            border-radius: 4px;
            transition: background-color 0.3s ease;
            font-weight: bold;
        }
        
        nav a:hover {
            background-color: #eee;
        }
        
        nav img {
            vertical-align: middle;
            margin-right: 8px;
            width: 24px;
            height: 24px;
        }

        section {
            max-width: 800px;
            margin: 6em auto 2em; /* Adds spacing below the fixed nav */
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
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</header>

    <nav>
        <a href="https://www.linkedin.com/in/mohsensadr/" target="_blank" title="LinkedIn">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" 
             alt="LinkedIn Logo" 
             style="width:24px; height:24px; vertical-align:middle;">
        </a>
        <a href="https://github.com/mohsensadr" target="_blank" title="GitHub">
            <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" style="width:24px; height:24px; vertical-align:middle;">
        </a>
        <a href="https://scholar.google.de/citations?user=YWJ0prAAAAAJ&hl=en&oi=ao" target="_blank" title="Google Scholar">
                <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg" 
         alt="Google Scholar Logo" 
         style="width:24px; height:24px; vertical-align:middle;"> 
        </a>
        <a href="https://orcid.org/0000-0003-0241-8163" target="_blank" title="ORCID">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" 
         alt="ORCID Logo" 
         style="width:24px; height:24px; vertical-align:middle;">
        </a>
        <a href="CV.pdf" download>
            <span class="material-icons" style="vertical-align: middle; margin-right: 5px;">description</span>
            Download CV
        </a>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#awards">Awards</a>
        <a href="#publications">Publications</a>
        <a href="#conferences">Conferences</a>
        <a href="#referee">Review</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p> My name is Mohsen. I am an applied mathematician with experience in data-driven/statistical modeling, Monte Carlo methods, density estimation, particle method, variance reduction, and optimal transport, with applications in rarefied gas and plasma dynamics as well as generative AI.</p>

             <p> Since July of 2023, I have been working on the optimal transport problem as a researcher at ETH, the Paul Scherrer Institute, in Switzerland. Here, I am also involved in upgrading <a href="https://gitlab.psi.ch/OPAL">OPAL</a>  (Object Oriented Particle Accelerator Library) to be exa-scalable and portable for simulating particle accelerators. In Dec. 2021, I joined MIT, USA, and worked with <strong>Prof. Nicolas Hadjiconstantinou</strong> on developing a general-purpose variance-reduced Monte Carlo method for kinetic equations. Before that, I worked with <strong>Prof. Laurent Villard</strong> at the Swiss Plasma Center (EPFL), Switzerland, as a postdoc on a particle-in-cell code for simulating plasma in confined geometry called <a href="https://www.epfl.ch/research/domains/swiss-plasma-center/research/theory/codes/research_theory_codes_orb5/">ORB5</a>. I carried out my doctoral studies at RWTH Aachen University, Germany, under the supervision of <strong>Prof. Manuel Torrilhon</strong> and <strong>Prof. Hossein Gorji</strong>. My <a href="https://doi.org/10.18154/RWTH-2020-07249">dissertation</a> was about developing efficient Monte Carlo methods for simulating dense gas, liquid, and phase transition descriptions in kinetic theory.
        </p>
        
    </section>

<section id="projects">
    <h2>Projects</h2>

        <h3>Statistical Modelling for Molecular Dynamics</h3>
    
    <p> In this line of research, we designed a stochastic process for modeling short and long-range interactions of monatomic particles that follows the exact kinetic equation up to desired moments with a feasible computational complexity that scales linearly with the number of particles. For details on the developed method, see [<a href="#FPmultiphase">6</a>, <a href="#LongRange">7</a>, <a href="#DFP">8</a>]. These methods have been implemented in a particle-in-cell code called <a href="https://github.com/piclas-framework/piclas">PICLas</a>. As a showcase, here a simulation of Argon's density experiencing the spinodal decomposition is presented.</p>

<div class="video-container">
    <iframe src="spinodal_4.mp4" frameborder="0" allowfullscreen></iframe>
</div>
      
    
 <h3>Excitation of Confined Plasma</h3>
    
    <p> Stabilizing a confined plasma in a fusion device is one of the main challenges in designing such a system. Often, it is worthwhile to study the growth/dissipation rates of modes of the system. I have worked on linear/non-linear excitation of Alfven modes in a confined plasma using a well-established particle-in-cell and gyrokinetic code called ORB5. As a showcase, electrostatic and magnetic potential fields are shown here where the mode of interest is successfully excited using a so-called antenna. For more details, see [<a href="#orb5">14</a>].</p>
     
     <img src="excitation_alfven_mode_confined_plasma.png" alt="Visualization of excited Alfven modes" class="responsive-img">

<h3>Variance Reduction Method</h3>

<p>One of the main challenges in interpreting the solution of statistical models is noise. We have developed a general-purpose and entropy-based variance reduction method for stochastic processes where the target density is around an equilibrium/control-variate density. In this project, we devised a consistent and least-biased evolution equation for the importance weights of the Boltzmann and Fokker-Planck equation. The following figures show the snapshot estimate of number density, bulk velocity, and temperature for the Sod-Shock tube test case. We also show how the noise varies with respect to the signal for the standard Monte Carlo and the introduced variance reduction method. For details, see [<a href="#VRDSMC">4</a>] and [<a href="#VRFP">5</a>]. </p>

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <div style="flex: 0 0 40%; max-width: 40%; box-sizing: border-box;">
        <img src="n_nv10_shock3.png" alt="Number density for Sod-Shock tube test case" style="width: 100%; height: auto; display: block;">
    </div>
    <div style="flex: 0 0 40%; max-width: 40%; box-sizing: border-box;">
        <img src="U_nv10_shock3.png" alt="Bulk velocity for Sod-Shock tube test case" style="width: 100%; height: auto; display: block;">
    </div>
    <div style="flex: 0 0 40%; max-width: 40%; box-sizing: border-box;">
        <img src="T_nv10_shock3.png" alt="Temperature for Sod-Shock tube test case" style="width: 100%; height: auto; display: block;">
    </div>
    <div style="flex: 0 0 40%; max-width: 40%; box-sizing: border-box;">
        <img src="var_shock.png" alt="Noise variation vs signal for variance reduction" style="width: 100%; height: auto; display: block;">
    </div>
</div>


<h3>Optimal Transport Problem</h3>
    
    <p> Finding the optimal map/plan between marginals is one of the most attractive problems in applied mathematics with applications in data-driven modeling and Machine Learning. I am interested in devising new dynamical systems to solve this problem more efficiently than standard methods. This includes collision-based dynamics [<a href="#colOT">1</a>], orthogonal coupling dynamics [<a href="#OCD">2</a>], and moment-based methods [<a href="#WE">3</a>]. As a showcase, here I show the output of a generative model trained using the optimal map between the normal and four other marginals. </p>
     
     <img src="5marginals.png" alt="Visualization of optimal transport for 5 marginals" class="responsive-img">


</section>

<section id="experience">
    <h2>Experience</h2>
    <h3>Scientist at ETH, Paul Scherrer Institute</h3>
    <p>Scientific Computing, Theory and Data</p>
    <p>Switzerland, Jul. 2023 - present</p>
    
    <h3>Fellow at Massachusetts Institute of Technology</h3>
    <p>Department of Mechanical Engineering</p>
    <p>USA, Dec. 2021 - Jun. 2023</p>

    <h3>Scientific Collaborator at EPFL</h3>
    <p>Swiss Plasma Center</p>
    <p>Switzerland, Oct. 2020 - Nov. 2021</p>
</section>

<section id="education">
    <h2>Education</h2>
    <h3>Ph.D. in Applied and Computational Mathematics</h3>
    <p>RWTH Aachen University, Germany, 2020</p>
    
    <h3>Master's in Simulation Sciences</h3>
    <p>RWTH Aachen University, Germany, 2017</p>
</section>

<section id="awards">
    <h2>Awards & Honors</h2>

    <li>
    Member of the team that won EUROfusion and SNSF project grant (consortium of national fusion research institutes, EU)
in 2021.
    </li>
    
    <li>
    Won the national Walter Benjamin scholarship offered by German research foundation (DFG) in 2020.
    </li>
    
    <li>
    Won the international grant from German academic exchange service (DAAD) in 2019.
    </li>
    
</section>


<section id="publications">
    <h2>Publications</h2>
    <ul>

        <strong>Optimal Transport:</strong>

        <li id="colOT">
        1. Mohsen Sadr and Hossein Gorji. "Collision-based dynamics for multi-marginal optimal transport" 2024 [<a href="https://doi.org/10.48550/arXiv.2412.16385">Preprint</a> | <a href="https://github.com/mohsensadr/collisional_ot">Code</a>].
        </li>

        <li id="OCD">
        2. Mohsen Sadr, Peyman Mohajerin Esfehani, and M. Hossein Gorji. "Optimal transportation by orthogonal
coupling dynamics" 2024 [<a href="https://doi.org/10.48550/arXiv.2410.08060">Preprint</a> | <a href="https://github.com/mohsensadr/OCD">Code</a>].
        </li>

         <li id="WE">
        3. Mohsen Sadr, Nicolas G. Hadjiconstantinou, and M. Hossein Gorji. "Wasserstein-penalized Entropy closure: A use case for stochastic particle methods" <em>Journal of Computational Physics </em>, 2024 [<a href="https://doi.org/10.1016/j.jcp.2024.113066">Elsevier</a> | <a href="https://arxiv.org/abs/2306.04120">Preprint</a> | <a href="https://github.com/mohsensadr/WE">Code</a>].
        </li>
        
        <strong>Variance Reduction:</strong>
        
        <li id="VRDSMC">
        4. Mohsen Sadr, and Nicolas G. Hadjiconstantinou. "A variance-reduced direct Monte Carlo simulation method for solving the Boltzmann equation over a wide range of rarefaction" <em>Journal of Computational Physics</em>, 472, 111677, 2023 [<a href="https://doi.org/10.1016/j.jcp.2022.111677">Elsevier</a> | <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4148310">Preprint</a>].
        </li>

        <li id="VRFP">
        5. Mohsen Sadr, and Nicolas G. Hadjiconstantinou. "Variance reduced particle solution of the Fokker-Planck equation with application to rarefied gas and plasma dynamics" <em>Journal of Computational Physics</em>, 492, 112402, 2023 [<a href="https://doi.org/10.1016/j.jcp.2023.112402">Elsevier</a> | <a href="https://dx.doi.org/10.2139/ssrn.4353547">Preprint</a>].
        </li>

        <strong>Modelling Phase Transition:</strong>
        
        <li id="FPmultiphase">
        6. Mohsen Sadr, Marcel Pfeiffer, and M. Hossein Gorji. "Fokker-Planck-Poisson kinetics: multi-phase flow beyond equilibrium" <em>Journal of Fluid Mechanics</em>, 920, A46, 2021 [<a href="https://doi.org/10.1017/jfm.2021.461">Cambridge University Press</a> | <a href="https://arxiv.org/abs/2308.05580">Preprint</a>].
        </li>

        <li id="LongRange">
        7. Mohsen Sadr, and M. Hossein Gorji. "Treatment of long-range interactions arising in the Enskog–Vlasov description of dense fluids" <em>Journal of Computational Physics</em>, 378, 129-142, 2019 [<a href="https://doi.org/10.1016/j.jcp.2018.11.005">Elsevier</a> | <a href="https://arxiv.org/abs/2308.05845">Preprint</a> | <a href="https://github.com/mohsensadr/Monte-Carlo-Particle-Method">Code</a>].
        </li>

        <li id="DFP">
        8. Mohsen Sadr, and M. Hossein Gorji. "A continuous stochastic model for non-equilibrium dense gases" <em>Journal of Physics of Fluids</em>, 29, 122007, 2017 [<a href="https://doi.org/10.1063/1.5004409">American Institute of Physics</a> | <a href="https://arxiv.org/abs/2308.05117">Preprint</a> | <a href="https://github.com/mohsensadr/Monte-Carlo-Particle-Method">Code</a>].
        </li>
        
        <strong>Data-Driven Modelling:</strong>
        
        <li>
        9. Mohsen Sadr, Tony Tohme, and Kamal Youcef-Toumi. "Data-driven discovery of PDEs via the adjoint method", 2024 [<a href="https://doi.org/10.48550/arXiv.2401.17177">Preprint</a> | <a href="https://github.com/mohsensadr/DiscoverPDEAdjoint">Code</a>].
        </li>

        <li>
        10. Tony Tohme, Mohsen Sadr, Kamal Youcef-Toumi, and Nicolas G. Hadjiconstantinou. "MESSY Estimation: Maximum-Entropy based Stochastic and Symbolic densitY Estimation" <em>Transactions on Machine Learning Research</em>, 2023 [<a href="https://arxiv.org/abs/2306.04120">Preprint</a> | <a href="https://github.com/mohsensadr/MESSY">Code</a>].
        </li>

        <li>
        11. Mohsen Sadr,  Manuel Torrilhon, and M. Hossein Gorji. "Gaussian Process Regression for Maximum Entropy Distribution" <em>Journal of Computational Physics</em>, 418, 109644, 2020 [<a href="https://doi.org/10.1016/j.jcp.2020.109644">Elsevier</a> | <a href="https://arxiv.org/abs/2308.06149">Preprint</a>].
        </li>

        <strong>Approximating Collision Operator:</strong>

        <li>
        12. Fabian Mies, Mohsen Sadr, and Manuel Torrilhon. "An efficient jump-diffusion approximation of the Boltzmann equation" <em>Journal of Computational Physics</em>, 490, 112308, 2023 [<a href="https://doi.org/10.1016/j.jcp.2023.112308">Elsevier</a> | <a href="https://arxiv.org/abs/2112.08362">Preprint</a>].
        </li>

        <li>
        13. Mohsen Sadr, Qian Wang, and M. Hossein Gorji. "Coupling kinetic and continuum using data-driven maximum entropy distribution" <em>Journal of Computational Physics</em>, 444, 110542, 2021 [<a href="https://doi.org/10.1016/j.jcp.2021.110542">Elsevier</a> | <a href="https://arxiv.org/abs/2308.05672">Preprint</a>].
        </li>

        <strong>Simulation of Plasma/Fluid:</strong>
        
        <li id="orb5">
        14. Mohsen Sadr, Alexey Mishchenko, Thomas Hayward-Schneider, Axel Koenies, Alberto Bottino, Alessandro Biancalani, Peter Donnel, Emmanuel Lanti, and Laurent Villard. "Linear and nonlinear excitation of TAE modes by external electromagnetic perturbations using ORB5" <em>Plasma Physics and Controlled Fusion</em>, 64, 085010, 2022 [<a href="https://iopscience.iop.org/article/10.1088/1361-6587/ac73eb">IOP Publishing Ltd (open access)</a>].
        </li>

        <li>
        15. P Donnel, J Cazabonne, L Villard, S Brunner, S Coda, J Decker, M Murugappan, and M Sadr. "Quasilinear treatment of wave–particle interactions in the electron cyclotron range and its implementation in a gyrokinetic code" <em>Plasma Physics and Controlled Fusion</em>, 63, 064001, 2021 [<a href="https://iopscience.iop.org/article/10.1088/1361-6587/abf53f">IOP Publishing Ltd (open access)</a>].
        </li>
        
        <li>
        16. Sima Farazi, Mohsen Sadr, Seongwon Kang, Martin Schiemann, Nikita Vorobiev, Viktor Scherer, Heinz Pitsch. "Resolved simulations of single char particle combustion in a laminar flow field" <em>Fuel</em>, 201, 15-28, 2017 [<a href="https://doi.org/10.1016/j.fuel.2016.11.011">Elsevier</a>].
        </li>
        
        
    </ul>
</section>


<section id="conferences">
    <h2>Conferences</h2>
    <ul>

        <li>
        5th Mathematical and Scientific Machine Learning, Naples, Italy, August 2025.
        </li>

        <li>
        30th Biennial Numerical Analysis Conference, Glasgow, UK, June, 2025.
        </li>

        <li>
        4th Mathematical and Scientific Machine Learning, Providence, USA, June 2023.
        </li>

        <li>
        19th European Fusion Theory Conference, virtual, October 2021.
        </li>

        <li>
        9th International Congress on Industrial and Applied Mathematics, Valencia, Spain, July 2019.
        </li>

        <li>
        10th International Conference on Multiphase Flow, Rio de Janeiro, Brazil, May 2019.
        </li>

        <li>
        3rd European Conference on Non-Equilibrium Gas Flows, Strasbourg, France, February 2018.
        </li>
        
    </ul>
</section>

<section id="referee">
        <h2>Review</h2>

        <p>
        I am an active referee of the following peer-reviewed journals/conferences:
        </p>
        
        <li>
             <a href="https://www.sciencedirect.com/journal/journal-of-computational-physics">Journal of Computational Physics</a>
        </li>

        <li>
             <a href="https://pubs.aip.org/aip/pof?gad_source=1&gbraid=0AAAAADgwGbzh-SiC9i39ahsUKgozB8sDJ&gclid=Cj0KCQjw1Yy5BhD-ARIsAI0RbXaaBDmB03R1ixhcDVy_1zWYKVKB8Ik_sG-5GmENfxe75-kplx7P0z8aAgYUEALw_wcB">Physics of Fluids (POF)</a>
        </li>

        <li>
             <a href="https://iclr.cc">International Conference on Learning Representations (ICLR)</a>
        </li>
        
        <li>
             <a href="https://link.springer.com/journal/11012">Meccanica</a>
        </li>

        <li> 
             <a href="https://www.sciencedirect.com/journal/advanced-powder-technology">Advanced Powder Technology</a>
        </li>
        
        <li>
            <a href="https://www.mdpi.com/journal/photonics">Photonics</a>
        </li>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>
            You can reach me at <a href="mailto:mohsen.sadr@psi.ch">mohsen.sadr@psi.ch</a> or <a href="mailto:mohsen.sadr91@gmail.com">mohsen.sadr91@gmail.com</a>.
        </p>
    </section>

    <footer>
        &copy; 2024 Mohsen Sadr. All rights reserved.
    </footer>

    <script>
        let lastScrollY = window.scrollY; // Tracks the last scroll position
        const nav = document.querySelector('nav');
        const scrollUpThreshold = 100; // Amount of upward scroll needed to show the nav
        let accumulatedScrollUp = 0; // Tracks how much we've scrolled up
        const mouseThreshold = 50; // Distance from the top of the page to detect mouse movement
        let clickOverride = false; // Prevents mouse movement from showing the nav after a click
        const clickOverrideDuration = 1000; // How long to suppress the mouse-triggered show (in ms)
    
        // Function to show the navigation bar
        function showNav() {
            if (!clickOverride) {
                nav.style.transform = 'translateY(0)';
                accumulatedScrollUp = 0; // Reset accumulated scroll up
            }
        }
    
        // Function to hide the navigation bar
        function hideNav() {
            nav.style.transform = 'translateY(-100%)';
        }
    
        // Scroll event listener
        window.addEventListener('scroll', () => {
            const currentScrollY = window.scrollY;
    
            if (currentScrollY === 0) {
                // User is at the top of the page, always show the navigation bar
                showNav();
                accumulatedScrollUp = 0; // Reset accumulated scroll up at the top
            } else if (currentScrollY > lastScrollY) {
                // User is scrolling down, hide the navigation bar
                hideNav();
                accumulatedScrollUp = 0; // Reset accumulated scroll up when scrolling down
            } else {
                // User is scrolling up
                accumulatedScrollUp += lastScrollY - currentScrollY; // Add the scroll-up distance
    
                if (accumulatedScrollUp >= scrollUpThreshold) {
                    // Show the navigation bar only if the threshold is met
                    showNav();
                }
            }
    
            lastScrollY = currentScrollY; // Update the last scroll position
        });
    
        // Mouse movement event listener
        window.addEventListener('mousemove', (event) => {
            if (event.clientY <= mouseThreshold) {
                // If the mouse is within the top threshold of the page, show the navigation bar
                showNav();
            }
        });
    
        // Click event listener on the navigation bar
        nav.addEventListener('click', () => {
            hideNav(); // Hide the navigation bar when it is clicked
            clickOverride = true; // Activate click override
            setTimeout(() => {
                clickOverride = false; // Reset override after a delay
            }, clickOverrideDuration);
        });
    </script>



    <script>
        // Prevent the page from scrolling to a hash on load
        window.addEventListener("load", function() {
            if (window.location.hash) {
                window.location.hash = "";
            }
        });
    </script>


</body>
</html>
