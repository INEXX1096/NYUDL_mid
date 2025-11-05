## Model Checkpoint

1.  **Download the Recommended Checkpoint:**
    * We provide two different trained models, but **we recommend `checkpoint-900`** for scoring.
    * Please download `checkpoint-900` from this link:
    * **Link:** [https://drive.google.com/drive/folders/1RlJBMgWpGDiDcNZ9d62VJ9hlEYAsBnY5?usp=drive_link](https://drive.google.com/drive/folders/1RlJBMgWpGDiDcNZ9d62VJ9hlEYAsBnY5?usp=drive_link)
    
    *(Note: An alternative model is available [here](https://drive.google.com/drive/folders/1Qvn5hjVnrKNXabhlT6R_MmkNZ1Oo9rKz?usp=drive_link), but `checkpoint-900` is the one used for our main submission.)*

2.  **Create Folder & Place File:**
    * Place the downloaded `checkpoint-900` folder inside this `Checkpoint/` folder.

    The final file path **must** match this structure exactly:
    `./Checkpoint/checkpoint-900/`

3.  **Run Inference:**
    * The `DL_Mid.ipynb` and `inference.ipynb` notebooks are configured to automatically load the model from the `./Checkpoint/checkpoint-900/` path.
