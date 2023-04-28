---
keywords: fastai
title: This page shows theme toggle
toc: true
comments: true
badges: false
nb_path: _notebooks/2023-04-22-theme-toggle.ipynb
layout: notebook
---
## Hacks Part 2

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="/FastPages/assets/css/light-theme.css">
    <link rel="stylesheet" href="/FastPages/assets/css/dark-theme.css" id="theme-link">
</head>
<body>
    <button id="theme-toggle">Toggle Theme</button>
    <script>
        const toggleButton = document.querySelector('#theme-toggle');
        const themeLink = document.querySelector('#theme-link');
        toggleButton.addEventListener('click', () => {
            if (themeLink.getAttribute('href') === '/FastPages/assets/css/light-theme.css') {
                themeLink.setAttribute('href', '/FastPages/assets/css/dark-theme.css');
            } else {
                themeLink.setAttribute('href', '/FastPages/assets/css/light-theme.css');
            }
        });
    </script>
</body>