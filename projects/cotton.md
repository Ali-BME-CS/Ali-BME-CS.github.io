---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "EEG Preprocessing"
date: 
published: false
labels:
  - Lisp
  - GitHub
summary: "EEG Preprocessing."
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

Cotton is a horror-style text-based adventure game I developed using the functions and macros built from The Wizard's Game in [Conrad Barski's Land of Lisp](http://landoflisp.com/). Slightly more interesting and convoluted! (It is not that scary.)

To give you a flavor of the game, here is an excerpt from one run:

<hr>
<!DOCTYPE html>
<html>
<head>
    <title>The Happe Pipeline: EEG Preprocessing for Robust Data Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }

        h1 {
            background-color: #2196F3;
            color: white;
            text-align: center;
            padding: 20px;
            margin: 0;
        }

        h2 {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
        }

        p {
            padding: 10px;
            margin: 0;
        }

        img {
            display: block;
            margin: 0 auto;
            max-width: 80%;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
        }

        .highlight {
            background-color: #FFC107;
            padding: 5px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>The Happe Pipeline: EEG Preprocessing for Robust Data Analysis</h1>

    <div class="container">
        <h2>Introduction</h2>
        <p>EEG (Electroencephalography) is a powerful tool for studying brain activity in both research and clinical settings. However, before EEG data can be analyzed, it often requires thorough preprocessing to ensure the removal of artifacts and the extraction of meaningful signals. One well-regarded EEG preprocessing pipeline is the Happe pipeline. In this essay, we will explore the Happe pipeline and its essential steps, emphasizing its significance in EEG research.</p>

        <p class="highlight">Yes, I know about the Happe pipeline for EEG preprocessing. It is a standardized, automated pipeline that can process EEG data from raw files to processed EEG suitable for time-frequency-domain analyses². It is especially designed for developmental and high-artifact data, such as those from young children or those with neurodevelopmental disorders².</p>

        <img src="eeg_preprocessing.png" alt="EEG Preprocessing" width="80%">

        <h2>The Happe Pipeline in Four Steps</h2>
        <p>The Happe pipeline consists of four main steps: pre-process, check, generate, and validate¹. Each step plays a crucial role in preparing EEG data for meaningful analysis.</p>

        <p>1. <strong>Pre-process</strong>: In this initial step, the raw EEG data undergoes a series of transformations. It includes filtering the data to remove noise and artifacts, identifying and removing bad channels and epochs, interpolating missing channel data, and re-referencing the data to a common reference point.</p>

        <p>2. <strong>Check</strong>: The check step allows the user to interactively inspect the pre-processed data. Researchers can manually review the data and make adjustments to processing parameters if necessary. This hands-on quality control ensures that the data is prepared to the highest standards.</p>

        <img src="eeg_inspection.png" alt="EEG Data Inspection" width="80%">

        <p>3. <strong>Generate</strong>: The generate step involves the extraction of specific features of interest from the pre-processed EEG data. This can include event-related potentials (ERPs) or resting-state power spectra, depending on the research objectives. These extracted features are vital for subsequent analyses.</p>

        <p>4. <strong>Validate</strong>: The final step, validate, computes data quality metrics and generates comprehensive reports for each processed EEG file¹. This transparency is essential for documenting the quality of the data and the preprocessing steps, ensuring rigor and reproducibility in EEG research.</p>

        <img src="data_quality.png" alt="Data Quality Metrics" width="80%">

        <h2>Advantages of the Happe Pipeline</h2>
        <p>The Happe pipeline has been shown to outperform seven alternative processing approaches in terms of removing more artifacts and preserving more signal in EEG data². This makes it particularly valuable for datasets with challenging characteristics, such as those from young children or individuals with neurodevelopmental disorders.</p>

        <p>Additionally, the Happe pipeline provides a consistent and transparent way of reporting data quality measures. This is crucial for EEG research, as the quality of the data greatly influences the reliability of subsequent analyses. By offering a standardized approach, the Happe pipeline promotes best practices and ensures that researchers can trust their results.</p>

        <h2>Conclusion</h2>
        <p>In the realm of EEG research, the Happe pipeline stands as a robust and reliable tool for data preprocessing. Its four-step approach, including pre-process, check, generate, and validate, ensures that EEG data is cleaned, analyzed, and validated with the utmost precision. Researchers can have confidence in the quality of their data and the transparency of their methods, ultimately leading to more meaningful insights into brain activity.</p>

        <p>The availability of the Happe pipeline as open-source software under the terms of the GNU General Public License further underscores its significance in advancing EEG research, making it a valuable asset for the scientific community.</p>
    </div>
</body>
</html>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
