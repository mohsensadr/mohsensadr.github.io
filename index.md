
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohsen Sadr - Welcome</title>
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

        h1, h2 {
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
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>
            Hello, I'm Mohsen, a Postdoc at Paul Scherer Institute since July 2023. I'm responsible for upgrading <a href="https://gitlab.psi.ch/OPAL">OPAL</a>  (Object Oriented Particle Accelerator Library) with the exa-scalable particle-in-cell library called <a href="https://github.com/IPPL-framework">IPPL</a>  (Independent Parallel Particle Layer) for simulating particle accelerators, plasma, and rarefied gas dynamics.
        </p>
        
        <p>
            In Dec. 2021, I joined MIT (Massachusetts Institute of Technology) and worked with Prof. Nicolas Hadjiconstantinou on developing a general-purpose variance reduction for Monte Carlo methods in kinetic theory. 
        </p>

        <p>
            You can find a list of my publications on <a href="https://scholar.google.com/citations?user=YWJ0prAAAAAJ&hl=en&oi=ao">Google Scholar</a>.
        </p> 
    </section>


<section id="publications">
    <h2>Publications</h2>
    <ul>
        <li>
            <strong>Mohsen Sadr and Nicolas G. Hadjiconstantinou </strong>. "A variance-reduced direct Monte Carlo simulation method for solving the Boltzmann equation over a wide range of rarefaction" <em>Journal of Computational Physics</em>, 472, 111677, 2023 [<a href="https://doi.org/10.1016/j.jcp.2022.111677">Elsevier</a>| <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4148310">Priprint</a> ].
        </li>
        
        <li>
            <strong>Mohsen Sadr, Marcel Pfeiffer, and M. Hossein Gorji </strong>. "Fokker-Planck-Poisson kinetics: multi-phase flow beyond equilibrium" <em>Journal of Fluid Mechanics</em>, 920, A46, 2021 [<a href="https://doi.org/10.1017/jfm.2021.461">Cambridge University Press</a>| <a href="https://arxiv.org/abs/2308.05580">Priprint</a> ].
        </li>
    </ul>
</section>


    <section id="contact">
        <h2>Contact</h2>
        <p>
            You can reach me at: <a href="mailto:mohsen.sadr@psi.ch">mohsen.sadr@psi.ch</a>
        </p>
    </section>

    <footer>
        &copy; 2023 Mohsen Sadr. All rights reserved.
    </footer>

</body>
</html>
