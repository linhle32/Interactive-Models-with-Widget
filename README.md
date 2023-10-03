# Interactive-Models-with-Widget

This repository includes some examples of using `iPyWidgets` to build simple interactive applications over a trained machine learning model. For tasks that involve large models, for example, with text or image data with AutoModel from `transformers`, modeling codes will be reused from HuggingFace's tutorials which are noted so in the specific notebooks.

The notebooks should be opened in Google Colab to ensure that outputs are displayed properly. All notebooks follow the below structure:
1. Data loading. Mostly just a few cells to load raw data into the session. A few notebooks have some cells to transfer data between `pandas` and `datasets` for convenience purpose.
2. Data processing and modeling. Building pipeline to transform data as well as select, train, or finetune models. In tasks with models from `transformers`, the codes here are summarized from HuggingFace's tutorials.
3. Application. Building a simple interactive application using `iPyWidgets`. In general, form fields are created for each required input, and the prediction task is attached to a button.
