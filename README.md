# EFramework-SeismicSelfDenoise2D

Add-on for [**EFramework**](https://github.com/RMiftakhov/EFramework) -  democratize the use of AI/ML tools for Energy.

This repo is an adaptation of the 2D Self Supervised Seismic Denoising by [Claire](https://cebirnie92.github.io/) (Links: [Paper](https://arxiv.org/abs/2109.07344), [GitHub](https://github.com/swag-kaust/Transform2022_SelfSupervisedDenoising))

## Step1 - EFramework Installation
1. Clone the repo `git clone https://github.com/RMiftakhov/EFramework`
2. Lauch a terminal in the EFramework folder
3. Create a new conda enviroment `conda env create -f environment.yml`
4. Activate the enviroment `conda activate EFramework`
5. `cd ../`

##  Step 2 - Install the add-on
1. Clone this repo `git clone https://github.com/RMiftakhov/EFramework-SeismicSelfDenoise2D`
2. Copy all the files from pages director `EFramework-SeismicSelfDenoise2D/pages/` to `EFramework/pages/`
3. Copy all the folders from `EFramework-SeismicSelfDenoise2D/appdata/` to `EFramework/appdata/`
4. Install `torch`  
for MacOS `conda install pytorch torchvision torchaudio -c pytorch` 
for Windows `conda install pytorch torchvision torchaudio cpuonly -c pytorch` or `conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch`
5. Goto folder `EFramework`
6. Run streamlit server `streamlit run Hello.py`



