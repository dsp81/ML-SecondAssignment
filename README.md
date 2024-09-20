# ML-SecondAssignment

Overview

This repository contains the solution files for the Machine Learning second assignment. The tasks involve employing different techniques for audio and image reconstruction, super resolution, image compression such as random fourier features, line regression and matrix factorisation. The repository includes Jupyter Notebooks with code implementations and analysis.

File Descriptions

task1_assignment2.ipynb Contains the solution for Task 1, which focuses on gradient descent.

task2audio.ipynb and task2video.ipynb provides the solution for Task 2, which focuses on image reconstruction using Random Fourier Features (RFF) and Linear Regression to map pixel coordinates to color values, as well as audio reconstruction from time to amplitude. It also reports RMSE and PSNR for the image and RMSE and SNR for the audio.

File task3final.ipynb contains the solution for Task 3, which demonstrates super-resolution on an image using Random Fourier Features (RFF) to enhance its resolution by a factor of 2. It includes qualitative comparisons of the original and reconstructed images, along with quantitative evaluations using RMSE and PSNR metrics.

File task4final.ipynb contains the solution for Task 4, which focuses on reconstructing an image using matrix factorization. It covers scenarios with missing pixel values, evaluates RMSE and PSNR for both matrix factorization and Random Fourier Features (RFF) reconstructions, and compares the performance of both methods.

File task5final.ipynb contains the solution for Task 5, which involves compressing a 50x50 image patch using matrix factorization. It explores different low-rank values for compression, computes RMSE and PSNR metrics for the reconstructed patches, and displays the results while maintaining original pixel values outside the patch.
