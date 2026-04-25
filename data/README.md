# Dataset Instructions

This folder is reserved for the Adult Income dataset files used by this project.

The dataset files are **not committed to GitHub**. To run the notebook locally, download the Adult Income dataset from the UCI Machine Learning Repository:

```text
http://archive.ics.uci.edu/ml/datasets/Adult
```

The assignment uses the Adult Income / Census Income dataset, which contains demographic and employment-related attributes and a target variable indicating whether a person's income exceeds $50,000 per year.

## Required File

For the current notebook workflow, place the following file inside this folder:

```text
adult.data
```

## Expected Local Structure

```text
data/
├── README.md
└── adult.data
```

Only `README.md` should be committed to GitHub. The actual dataset file should remain local.

## Expected Path

Because the notebook is located inside the `notebooks/` folder, the notebook expects the dataset at:

```python
../data/adult.data
```

If you run code from the repository root instead, use:

```python
data/adult.data
```

## Optional Files

Other UCI Adult dataset files, such as:

```text
adult.test
adult.names
Index
```

can also be kept locally in this folder, but they are not required for the current notebook workflow.

## Notes

- The dataset is intentionally excluded from this repository to keep the GitHub project lightweight.
- The `adult.data` file does not include column headers, so the notebook defines the column names manually.
- If your local filename differs, either rename it to `adult.data` or update the notebook path accordingly.
