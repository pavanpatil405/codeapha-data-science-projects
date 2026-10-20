# CodeAlpha Data Science Projects

Beginner-friendly notebooks and guides for three CodeAlpha data science projects: Iris flower classification, unemployment analysis, and car price prediction.

## Projects

| Project | Notebook | Beginner guide |
| --- | --- | --- |
| Iris Flower Classification | [`notebooks/CodeAlpha_Iris_Flower_Classification.ipynb`](notebooks/CodeAlpha_Iris_Flower_Classification.ipynb) | [`guides/CodeAlpha_Iris_Beginner_Guide.pdf`](guides/CodeAlpha_Iris_Beginner_Guide.pdf) |
| Unemployment Analysis | [`notebooks/CodeAlpha_Unemployment_Analysis.ipynb`](notebooks/CodeAlpha_Unemployment_Analysis.ipynb) | [`guides/CodeAlpha_Unemployment_Beginner_Guide.pdf`](guides/CodeAlpha_Unemployment_Beginner_Guide.pdf) |
| Car Price Prediction | [`notebooks/CodeAlpha_Car_Price_Prediction.ipynb`](notebooks/CodeAlpha_Car_Price_Prediction.ipynb) | [`guides/CodeAlpha_Car_Price_Prediction_Beginner_Guide.pdf`](guides/CodeAlpha_Car_Price_Prediction_Beginner_Guide.pdf) |

Additional material:

- [`resources/CodeAlpha_GitHub_and_Video_Presentation_Tasks_1_2_3.pdf`](resources/CodeAlpha_GitHub_and_Video_Presentation_Tasks_1_2_3.pdf) — task and presentation guidance.
- [`resources/Netflix_Project_Natural_Voiceover_Script.pdf`](resources/Netflix_Project_Natural_Voiceover_Script.pdf) — narration script for a separate Netflix content analysis project.

## Run the notebooks

You can open the notebooks in Jupyter or upload them to Google Colab. For a local Python environment:

```bash
python -m pip install -r requirements.txt
jupyter lab
```

Run each notebook from top to bottom. The Iris notebook uses scikit-learn's built-in dataset. The unemployment and car-price notebooks retrieve their example datasets from public URLs; check each notebook's data-loading section for details and fallback instructions.

## Notes

- The notebooks are educational examples. Review dataset definitions, units, and limitations before interpreting results.
- Dataset availability depends on the external sources remaining accessible.
- Generated charts and model files are not included in this repository.
