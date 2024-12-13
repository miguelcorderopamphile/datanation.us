Greetings everyone!

##Overview##
'Datanation.us' is an open-source data project to explore and identify patterns in U.S. economic data utilizing techniques in data engineering, analytics, and deep learning.

Our goal with this approach is to achieve a clear understanding about the U.S. as a data-driven nation. (that's why the name of the project).

The data is sourced from two official providers: The Federal Reserve with the FRED API and the U.S. Bureau of Labor Statistics with BLS Public Data API.

######For references, please see:
https://fred.stlouisfed.org/docs/api/fred/ 
https://www.bls.gov/developers/api_signature_v2.htm

###Setup virtual environment:
Note: This setup has only been proven to function in Linux environments.

######You need to install Anaconda following their their official steps:
https://www.anaconda.com/download/success
https://docs.anaconda.com/anaconda/install/
Hint: When it is time to accept the license and usage agreements, press 'q' and you can continue with the installation.

######After your Anaconda configuration has been finalized, we go to clone the repository and start the virtual environment:
```bash
git clone https://github.com/miguelcorderopamphile/datanation.us
cd ./datanation.us
```

######Setting up Anaconda Environment:
```bash
#script 
conda create --prefix "$HOME/datanation.us/venv_datanation.us" python=3.12 -y
```

```bash
conda activate "$HOME/datanation.us/venv_datanation.us"
```

Note: If you want to deactivate the virtual environment execute 'conda deactivate'.
