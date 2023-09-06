# Webscrapping study

Group members: 
- Leonardo Ripes Moura da Rosa
- Marcelo 
- Vitor Hugo Garcez

This study was carried out for a work at the university in the discipline of data collection, preparation and analysis.

We have two jupyter notebooks, the first is a study in a controlled environment and the second is a study in a real environment.

## How to run

Install the requirements to make sure that you can run the ipynb code.

```bash
pip install requirements.txt
```

### Crawler_control_env

To run this notebook first you need to run a local server so you can test there.


1. make sure that you have a python environment manager like conda
1. open terminal
1. unzip `server_e_aplicacao_para_scraping.zip`
2. run ```cd server_e_aplicacao_para_scraping```
2. using another python environment with python2
1. run `python -m pip install Pillow`
3. run `python .\web2py.py`
4. The GUI will open and allow you to enter a password and start using the web application. If you are using the default options, the address where you will access the site is http://127.0.0.1:8000/places/

> Whenever you start the server, put a password for the admin user, otherwise it will not be possible to access the configuration interface.

Now with the local website up you can run the `crawler_control_env.ipynb` notebook using another environment with python3 and the requirements.

## Crawler_real_env
To run this notebook you only need a python3 environment with the `requirements.txt` installed.
