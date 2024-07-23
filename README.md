# gsindice_cluster_analysis

## Description

Factor investments, also known as factor-based investing or smart beta, involve constructing portfolios based on certain characteristics or factors that have been shown to influence the performance of stocks or other assets. These factors are used to capture specific risks and potential returns that are not adequately explained by traditional market indices.

This project aims to turn general investment instruments or indices into factors. This is done by grouping them into factors based on commonly shared characteristics. However, this is difficult as there are many factors to consider with the various investment instruments that exist. Therefore, a automative approach is taken and the project utilizes cluster analysis in the form of principal component analysis. This project is based on real return data from actual investment instruments provided by Goldman Sachs.

## Usage

There is one main source code file, coded on python 3 and ran on Jupyter. It is named "Cluster analysis of GS indices". The data used is included in a seperate excel file and was collected from Bloomberg Terminal. The data is altered due to legal issues. However, the code still works with the altered data.

## Installation instructions

1. Download all the files
2. Ensure pandas, numpy, matplotlib, and sklearn are downloaded in the environment
3. Run the main source code on Jupyter Lab or Notebook
4. Restart and run all kernels 

## Extensions

1. Other ways to group investment instruments may include manually listing a stream of characteristics and using code to automate a rank based on each characteristic for each investment instrument. E.g., investment instrument is the most volatile so it is assigned a rank of 5 out of 5.
2. Once the investment instruments are grouped together into factors, what would be the next step in statically or dynamically weighing them in a portfolio?
