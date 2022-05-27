# cal_adapt_notebooks

## AWS SageMaker Studio Lab
You can sign up for SageMaker Studio Lab and use it for free without an AWS account. You can run for 4 hours with GPU or 12 hours with CPU and then logout and log back in for another session. Your data and notebooks are persisted. After clicking the launch button below, choose "download whole repo" but DO NOT "build conda environment" when prompted (it will fail). Open a Terminal, and paste this command:

conda create -n cal_adapt_notebooks --file https://raw.githubusercontent.com/pangeo-data/pangeo-docker-images/2021.12.02/pangeo-notebook/conda-linux-64.lock

...which will build the conda environment from an exact image.  Once it's complete, activate the conda environment with this command:

conda activate cal_adapt_notebooks

Now, open the "select_to_export.ipynb" notebook.  Click-Enter to run each row and wait a moment to see the results of each line before proceeding to the next. The line marker should change to a number when it's successfully run that line, ie "[5]" means that it has run line 5.

<a href="https://studiolab.sagemaker.aws/import/github/https://github.com/cstner/cal_adapt_notebooks/blob/main/select_to_export.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/8c5378ff3bf6f71a57442940234293bd63c7ed2418d64f74f2bda3dc6f2904ed/68747470733a2f2f73747564696f6c61622e736167656d616b65722e6177732f73747564696f6c61622e737667" alt="Open In SageMaker Studio Lab" data-canonical-src="https://studiolab.sagemaker.aws/studiolab.svg" style="max-width: 100%;"></a></p>

