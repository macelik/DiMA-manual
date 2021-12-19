Welcome to DiMA Help Page's documentation!
===================================

**DiMA** is designed to facilitate the dissection of protein sequence diversity dynamics for viruses. DiMA provides a quantitative measure of sequence diversity by use of Shannon’s entropy, applied via a user-defined kmer sliding window. Further, the entropy value is corrected for sample size bias by applying a statistical adjustment. Additionally, DiMA further interrogates the diversity by dissecting the entropy value at each kmer position to various diversity motifs. The distinct kmer sequences at each position are classified into the following motifs based on their incidence. Index is the predominant sequence, and all other distinct kmers are referred to as total variants, sub-classified into major variant (the predominant variant), minor variants (kmers with the incidence in between major and unique motifs) and unique variants (seen once in the alignment). Moreover, the description line of the sequences in the alignment can be formatted for inclusion of meta-data that can be tagged to the diversity motifs. DiMA enables comparative diversity dynamics analysis, within and between proteins of a virus species, and proteomes of different viral species.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
