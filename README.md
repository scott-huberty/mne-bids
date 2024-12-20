[![Codecov](https://codecov.io/gh/mne-tools/mne-bids/branch/main/graph/badge.svg)](https://codecov.io/gh/mne-tools/mne-bids)
[![GitHub Actions](https://github.com/mne-tools/mne-bids/workflows/build/badge.svg)](https://github.com/mne-tools/mne-bids/actions)
[![CircleCI](https://circleci.com/gh/mne-tools/mne-bids.svg?style=shield)](https://circleci.com/gh/mne-tools/mne-bids)
[![PyPI Download count](https://pepy.tech/badge/mne-bids)](https://pepy.tech/project/mne-bids)
[![Latest PyPI release](https://img.shields.io/pypi/v/mne-bids.svg)](https://pypi.org/project/mne-bids/)
[![Latest conda-forge release](https://img.shields.io/conda/vn/conda-forge/mne-bids.svg)](https://anaconda.org/conda-forge/mne-bids/)
[![JOSS publication](https://joss.theoj.org/papers/5b9024503f7bea324d5e738a12b0a108/status.svg)](https://joss.theoj.org/papers/5b9024503f7bea324d5e738a12b0a108)

MNE-BIDS
========

MNE-BIDS is a Python package that allows you to read and write
[BIDS](https://bids.neuroimaging.io/)-compatible datasets with the help of
[MNE-Python](https://mne.tools/stable/index.html).

![Schematic: From raw data to BIDS using MNE-BIDS](https://mne.tools/mne-bids/assets/MNE-BIDS.png)

Why?
----

MNE-BIDS links BIDS and MNE-Python with the goal to make your analyses faster to code and more robust,
and to facilitate data and code sharing with co-workers and collaborators.

Having your data in BIDS format also allows the use of automated pipelines, for example [mne-bids-pipeline](https://mne.tools/mne-bids-pipeline/stable/).

How?
----

The documentation can be found under the following links:

- for the [stable release](https://mne.tools/mne-bids/)
- for the [latest (development) version](https://mne.tools/mne-bids/dev/index.html)

Getting Help
------------
[<img alt="MNE Forum" src="https://user-images.githubusercontent.com/1681963/52239617-e2683480-289c-11e9-922b-5da55472e5b4.png" height=60/>](https://mne.discourse.group)

For any usage questions, please post to the [MNE Forum](https://mne.discourse.group).
Be sure to add the `mne-bids` tag to your question.

Citing
------

[![JOSS publication](https://joss.theoj.org/papers/5b9024503f7bea324d5e738a12b0a108/status.svg)](https://joss.theoj.org/papers/5b9024503f7bea324d5e738a12b0a108)

If you use MNE-BIDS in your work, please cite our
[publication in JOSS](https://doi.org/10.21105/joss.01896):

> Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C.,
Chaumon, M., Mikulan, E., Tavabi, K., Höchenberger, R., Welke, D., Brunner, C.,
Rockhill, A., Larson, E., Gramfort, A., & Jas, M. (2019): **MNE-BIDS: Organizing
electrophysiological data into the BIDS format and facilitating their analysis.**
*Journal of Open Source Software,* 4:1896. DOI: [10.21105/joss.01896](https://doi.org/10.21105/joss.01896)

Please also cite one of the following papers to credit BIDS, depending on which data type you used:

- [MEG-BIDS](https://doi.org/10.1038/sdata.2018.110)
- [EEG-BIDS](https://doi.org/10.1038/s41597-019-0104-8)
- [iEEG-BIDS](https://doi.org/10.1038/s41597-019-0105-7)
- [NIRS-BIDS](https://doi.org/10.31219/osf.io/7nmcp)
