## **NOTICE: this repo is deprecated. The functionality here has been incorporated into [a-newman/mturk-template](https://github.com/a-newman/mturk-template). Please see [this notebook](https://github.com/a-newman/mturk-template/blob/master/mturk/mturk.ipynb).**

Notebook to interface with the MTurk API for ease of monitoring HITs. 

Provides methods to create HITs, pretty-print HIT and assignment status, expire/edit HITs, create qualifications, and download collected data. 

Requires Python3 and the following packages: 
- boto3 
- beautiful soup 4

Before using, you will have to set up an authentication key to use the Amazon API and include it in a credentials file. See here: https://aws.amazon.com/developers/getting-started/python/
