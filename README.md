
 # Video Classification 

Repository for video classification projects using TensorFlow.
Video classification involves the categorization of video content into predefined classes or categories based on the actions, events, or objects present in the video. It plays a crucial role in various applications such as surveillance, sports analysis, medical imaging, and entertainment.

## Dataset Information

UCF101 - Action Recognition Data Set

UCF101 is an action recognition dataset of realistic action videos, collected from YouTube, containing 101 action categories. With 13320 videos from 101 action categories, UCF101 offers diversity in actions and challenges due to variations in camera motion, object appearance, pose, scale, viewpoint, background clutter, illumination conditions, etc.

### Categories

The action categories are divided into five types:
1. Human-Object Interaction
2. Body-Motion Only
3. Human-Human Interaction
4. Playing Musical Instruments
5. Sports

For detailed categories, refer to the [UCF101 dataset website](https://www.crcv.ucf.edu/data/UCF101.php).



## Acknowledgments

UCF101 dataset is provided by the First International Workshop on Action Recognition with Large Number of Classes, ICCV'13.

For more information and published results, visit the [UCF101 dataset website](https://www.crcv.ucf.edu/data/UCF101.php).


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
