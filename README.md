# Effect of temporal window on HR estimation

## Setup
This project is designed to run in Google Colab, but should also work in any Jupiter Notebook (perhaps, excluding the cell with console commands).

## Description
It is well-known that heart rate (HR) changes over time. In some disciplines such as Remote Photoplethysmography [1], errors in the HR estimation per method are typically compared without considering the factor of different processing window sizes.

This project is aimed on measuring an value of "errors" in heart rate, estimated in time windows of different sizes. The Fantasia Database Subset [2] is used to extract real RR-intervals and to compute corresponding HR estimations for different temporal windows.

## Bibliography
1. M. Kopeliovich, Y. Mironenko and M. Petrushan, "Architectural Tricks for Deep Learning in Remote Photoplethysmography," 2019 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW), Seoul, Korea (South), 2019, pp. 1688-1696.
2. Iyengar N, Peng C-K, Morin R, Goldberger AL, Lipsitz LA. Age-related alterations in the fractal scaling of cardiac interbeat interval dynamics. Am J Physiol 1996;271:1078-1084.
