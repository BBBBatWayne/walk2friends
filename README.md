# walk2friends
This repository provides a reference implementation of *walk2friends* as described in the paper:<br>
> walk2friends: Inferring Social Links from Mobility Profiles. <br>
> Michael Backes, Mathias Humbert, Jun Pang, and Yang Zhang. <br>
> The 24th ACM SIGSAC Conference on Computer and Communications Security (CCS). <br>
> <Insert paper link>

## Basic Usage

### Example
To run our social link inference attack on the New York data with each user having at least 20 check-ins, please exucte the following command in folder src/: 

<br/>``python main_attack.py ny 20``

## Requirements
* pandas
* numpy
* scipy
* scikit-learn

It is recommended to install [Anaconda](https://www.continuum.io/downloads), a python data science distribution, which includes all the above packages.

* gensim
* joblib

## Citing
If you find walk2friends useful in your research, please cite the following paper:<br>
> @inproceedings{BHPZ17,<br>
>     author = {Michael Backes and Mathias Humbert and Jun Pang and Yang Zhang},<br>
>     title = {walk2friends: Inferring Social Links from Mobility Profiles.},<br>
>     booktitle = {Proceedings of the 24th ACM SIGSAC Conference on Computer and Communications Security (CCS)},<br>
>     year = {2016},<br>
>     publisher = {ACM}<br>
>  }<br>

## Miscellaneous
If you have any questions about the code and/or the algorithm, please send an email to <yang.zhang@cispa.saarland>.
