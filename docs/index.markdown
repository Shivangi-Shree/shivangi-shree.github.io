---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: "About"
permalink:/About
name: "About"
weight: 1
---
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.8">
    <style>
        .content {
            text-align: justify;
            hyphens: auto;
            position: relative;
        }
        .logo {
            float: right;
            margin-left: 10px;
            width: 160px;
        }
        a {
            color: #3471eb;
            text-decoration: underline;
        }
        .news-links {
            margin-top: 20px;
        }
        .news-item {
            max-width: 600px;
        }
        .news-date {
            width: 120px;
            text-align: left;
            font-weight: bold;
        }
        .news-link {
            flex-grow: 1;
        }
    </style>
</head>
<body>
    <div class="content">
        <p><img src="{{ site.baseurl }}/images/IIT_Patna_logo.png" alt="IIT Patna, Bihta" class="logo"></p>
        <p style="font-size: 22px; font-weight: bold;">Group</p>
        <p>at <strong><a href="https://srmap.edu.in/"> SRM University - AP, Amaravati (India)</a></strong></p>

        <p>Our new research group at IIT Patna is dedicated to exploring Integrated Quantum Systems. Our research focusing on 2D materials, semiconductor nanostructures, and hybrid interfaces, where quantum confinement effects play a crucial role in shaping electronic and optical properties. By leveraging these effects, we aim to achieve precise control over exciton dynamics, charge carrier behavior, and light-matter interactions for the deveopment of optoelectronics and quantum technologies. </p>

        <p><span style="color: #006600;"> We currently have bachelor's, master's, and PhD positions available. If interested, please reach out to discuss potential projects.</span></p>

        <div class="news-links">
            <h2 style="color: #663300;">News</h2>

            <div class="news-item" style="margin-top: 10px;">
                <div style="display: flex; align-items: center; gap: 5px;">
                    <div class="news-date">Feb. 13 </div>
                    <div class="news-link">
                        <a href="https://arxiv.org/abs/2502.09361" target="_blank">
                            New Preprint available
                        </a>
                    </div>
                </div>
            </div>

            <div class="news-item" style="margin-top: 10px;">
                <div style="display: flex; align-items: center; gap: 5px;">
                    <div class="news-date">Jan. 6 </div>
                    <div class="news-link">
                        <a href="https://iopscience.iop.org/article/10.1088/1751-8121/ad8f06/meta" target="_blank">
                            Paper published in <em>J. Phys. A: Math. Theor.</em>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

