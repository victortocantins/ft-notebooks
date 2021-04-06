# ft-notebooks

[![binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/geoscixyz/geosci-labs/master?filepath=notebooks%2Findex.ipynb)
[![pypi](https://img.shields.io/pypi/v/geoscilabs.svg)](https://pypi.python.org/pypi/geoscilabs)
[![License](https://img.shields.io/github/license/geoscixyz/geosci-labs.svg)](https://github.com/geoscixyz/geosci-labs/blob/master/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

Este é um repositório de código usado para alimentar os blocos de notas e exemplos interativos para
disciplina Física da Terra. Os notebooks podem usar pacotes desenvolvidos pelo autor ou por outros desenvolvedores como
como os projetos https://gpg.geosci.xyz e https://em.geosci.xyz.

## Por que?

As visualizações interativas são uma maneira poderosa e natural de interpretar as equações matemáticas. 
O objetivo deste repositório é fornecer os códigos que podem ser conectado a notebooks Jupyter usados com as equações relevantes
ao estudo dos fenômenos da Física da Terra

## Alcance

O repositório contém o código python para executar os aplicativos de estilo ipython-widget. Trata-se principalmente de código de plotagem e algumas análises simples. Simulações numéricas mais complexas dependem de [SimPEG] (http://simpeg.xyz)

## Uso

Os notebooks podem ser executados online pelo [Binder](#Binder), or [fazendo o download e executado localmente](#Localmente).

### Binder

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/geoscixyz/geosci-labs/master?filepath=notebooks%2Findex.ipyn)

1. Launch the binder by clicking on the badge above or going to: https://mybinder.org/v2/gh/geoscixyz/geosci-labs/master?filepath=notebooks%2Findex.ipynb.
   This can sometimes take a couple minutes, so be patient...

2. Select the notebook of interest from the contents

3. [Run the Jupyter notebook](#Running-the-notebooks)

![Binder-steps](https://em.geosci.xyz/_images/binder-steps.png)

### Locally

To run them locally, you will need to have python installed, preferably through [anaconda](https://www.anaconda.com/download/).

You can then clone this reposiroty. From a command line, run

```
git clone https://github.com/geoscixyz/geosci-labs.git
```

Then `cd` into `geosci-labs`

```
cd geosci-labs
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate geosci-labs
```

alternatively, you can install dependencies through pypi
```
pip install -r requirements.txt
```

You can then launch Jupyter
```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

![cell-run-all](https://em.geosci.xyz/_images/run_all_cells.png)

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

## Using in a course

## Issues

If you run into problems or bugs, please let us know by [creating an issue](https://github.com/geoscixyz/geosci-labs/issues/new) in this repository.

## For Contributors

We are glad you are interested in contributing! Please check out the [contributing guide](CONTRIBUTING.md) for ideas of how to get involved. 

