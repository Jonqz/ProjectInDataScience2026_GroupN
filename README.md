# Projects in Data Science (2026)
Collaborators: Jonas, Klara, Nyasha, Maksims.
#### Overview

This is a template repository for the "Projects in Data Science" course. You should use this repository for your project.

If using github.itu.dk, you need to download the repository and make your own. 

If you are using general Github, you can clone or fork the repository directly. 

Your repository MUST be named 2026-PDS-XX where XX is your group name (e.g. 2026-PDS-Pandas). 

#### Python environment

Follow TA instructions when setting up the Python environment before running any code. Remember to export your Python library requirements by `pip freeze > requirements.txt` and attach it to the repo so we can evaluate your scripts.

#### File Hierarchy

The file hierarchy of your hand-in repo should be as follows:

```
ProjectInDataScience2026_ExamTemplate/
├── data/
│   ├─ features.csv         # all image file names, ground-truth labels, and chosen features
│   │
│   ├── imgs/               # skin images (to not add on GitHub)
│   │    ├── img_XX1.png
│   │    ├── img_XX2.png
│   │     ......
│   │    └── img_XXX.png
│   │
│   └── masks/              # masks images (to not add on GitHub)
│        ├── mask_XX1.png
│        ├── mask_XX2.png
│         ......
│        └── mask_XXX.png
│
├── src/
│   ├── __init__.py
│   ├── feature_A.py    # code for feature A extraction
│   ├── feature_B.py    # code for feature B extraction
│   ......
│   └── feature_X.py    # code for feature X extraction
│ 
├── result/
│   ├── figures/        # Figures used in your report
│   ├── models/         # Trained models
│   ├── predictions/    # Probabilities outputed by the models
│   └── reports         # Files related to the Mandatory assignment
│        ├── report_GROUPEID.pdf
│        └── features_GROUPEID.csv
│ 
├── main.py             # script to train or evaluate models
└── README.md
```

**Notes:**

1. DO NOT upload your data (images) to Github.
2. When the same code block needs to be executed multiple times in the script, make it a custom function instead. All the custom functions and modules should be grouped into different files under the *"src"* subfolder, based on the task they are designed for. Do not put everything in a single Python file or copy-paste the same code block across the script.
