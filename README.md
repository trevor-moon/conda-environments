# conda-environments

My conda environments :snake:

These are the environments I commonly use for different projects. Most, if not all environments are are exported for cross-platform use

```text
conda env export --file envname.yml --from-history
```

## Install

To clone with https

```text
git clone https://github.com/trevor-moon/conda-environments.git
```

or clone with GitHub CLI

```text
gh repo clone trevor-moon/conda-environments
```

or locate the file you want, view the *Raw* file, copy, and paste

## Create the environment

Create the conda environment from file

```text
conda env create --file env/envname.yml
```

## Activate the environment

Activate the environment

```text
conda activate envname
```
