# Dataset Instructions

This folder is reserved for the Adult Income dataset files.

The dataset files are not committed to GitHub. To run the notebook locally, download the Adult Income dataset from the UCI Machine Learning Repository and place the file below in this folder:

```text
adult.data
```

Expected local structure:

```text
data/
├── README.md
└── adult.data
```

The notebook expects the dataset at:

```python
../data/adult.data
```

because the notebook is located inside the `notebooks/` folder.

Optional files such as `adult.test`, `adult.names`, or `Index` can also be kept locally in this folder, but they are not required for the current notebook workflow.
