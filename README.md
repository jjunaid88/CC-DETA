# CC-DETA

## Dataset

The datasets used in this project can be accessed through the following official sources:

### 1. Download from Official Website
Please refer to the official website for the original dataset files: [https://www.unb.ca/cic/datasets/iotdataset-2023.html]

### 2. Download from Google Drive
Alternatively, you can access the dataset via the following Google Drive link: [https://drive.google.com/drive/folders/1VixVjFAHsyOKVFUA1OKOl3-G3m01XVNe?usp=sharing]

## Usage

### Step 1: Set the Project Root Path

Modify the path in Cell 3 to store the results.

```python
PROJECT_ROOT = "/content/drive/MyDrive/DETA_Reviewer_Rebuild"
```

### Step 2: Set Up the CICIoT2023 Dataset

Ensure the dataset is accessible via a Google Drive shortcut named `CICIoT2023` at:

```
/content/drive/MyDrive/CICIoT2023
```

**Option A:** Create a shortcut in your Google Drive pointing to the dataset folder.

**Option B:** Place the dataset folder directly at the path above.

The expected directory structure:

```
/content/drive/MyDrive/CICIoT2023/
└── MERGED_CSV/
    ├── part-00000-xxx.csv
    ├── part-00001-xxx.csv
    └── ... (63 CSV files total)
```

### Step 3 (Optional): Verify the Dataset

Run **Cell 3C** to confirm the dataset is loaded correctly. This step performs an initial audit and saves metadata to the reproducibility folder.

Expected output:

```
CSV files found: 63
All files have identical schema: True
Possible target columns: ['Label']
```

> **Note:** If the dataset path is correct, you can skip this step and proceed directly to the main pipeline execution.
> 
## Citation
[Add citation details if applicable]
