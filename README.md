# CitationsInDynamics

Dataset contains dynamic co-citation network comprising 42 researchers who were active and participated in biannual IFCS Conferences in 1997-2016. This network is organized as 10 biannual co-citation graphs.

Data in ```researchers_citations.csv``` is organised in the following way:

- i - source node
- j - target node
- period - number from 1 to 10 corresponding to one of biannual periods: 1997-1998, 1999-2000,...,2015-2016
- weight - number of citations in period.

If you use this dataset in your work, please, refer to the following paper:

@inproceedings{rodin2017supercluster,
  title={Supercluster in Statics and Dynamics: An Approximate Structure Imitating a Rough Set},
  author={Rodin, Ivan and Mirkin, Boris},
  booktitle={International Joint Conference on Rough Sets},
  pages={576--586},
  year={2017},
  organization={Springer}
}
