---
layout: page
title: "Useful Resources"
permalink: /useful_resources/
weight: 5

---

Here is a collection of useful resources.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(2, minmax(200px, 1fr));
            gap: 20px;
            max-width: 700px;
            width: 100%;
        }
        .box {
            background: #e0f7fa;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease-in-out;
            text-align: left;
        }
        .box:hover {
            transform: scale(1.05);
        }
        .box ul {
            padding-left: 20px;
        }
        .box ul li {
            margin-bottom: 10px;
        }
        .box a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box">
            <p><strong>Entropy in Statistical Physics</strong></p>
            <ul>
                <li><a href="https://arxiv.org/pdf/1903.11870" target="_blank">Origin of the Zeroth Law of Thermodynamics and its Role in Statistical Mechanics</a></li>
                <li><a href="https://arxiv.org/pdf/1903.11870" target="_blank">Gibbs and Boltzmann Entropy in Classical and Quantum Mechanics</a></li>
                <li><a href="https://doi.org/10.1119/1.1971557" target="_blank">Gibbs vs Boltzmann Entropies (Am. J. Phys. 33, 391–398, 1965)</a></li>
            </ul>
        </div>
        <div class="box">
            <p><strong>Github</strong></p>
            <ul
                <<li><a href="https://www.coursera.org/in/articles/what-is-github" target="_blank"> Why to use Github?</a></li>
                <<li><a href="https://www.geeksforgeeks.org/introduction-to-github/Inroduction to Github" target="_blank"> Introduction to Github</a></li>
                <<li><a href="https://www.geeksforgeeks.org/useful-github-commands/" target="_blank"> Github commands </a></li>
                <li>Upcoming seminar on non-equilibrium physics.</li>
            </ul>
        </div>
    </div>
</body>
</html>


