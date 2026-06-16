# Body-Fat-Prediction-Model
A ML model that allow to predict body fat. 
* data/        # NEVER push raw data to GitHub if it's huge; include a link instead
* notebooks/             # Messy/Exploratory work (01_eda.ipynb, 02_modeling.ipynb)
* src/                   # Clean, production-ready code
    * preprocessing.py
    * feature_selection.py
* README.md              # The face of your project
* requirements.txt       # Software dependencies

├── 📂 data/                   # Dataset storage (Large raw files are git-ignored)
├── 📂 notebooks/              # Exploratory prototyping & research
│   ├── 01_eda.ipynb           # Data distributions & correlation analysis
│   └── 02_modeling.ipynb      # Model training, tuning, and evaluation
├── 📂 src/                    # Modular, production-ready source code
│   ├── preprocessing.py       # Data cleaning and scaling pipeline
│   └── feature_selection.py   # Dimensionality reduction & feature engineering
├── 📄 requirements.txt        # Project software dependencies
└── 📄 README.md               # Project documentation
