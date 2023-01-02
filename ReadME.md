# NLP Product Classifier


As part of a Product initiative, the Data Science team is asked to develop a solution to properly classify listings that fall between two categories: **0-Cellphones** and **1-Computers**. We could use a lot of data from existing items (title, description, images, price, and other fields and metadata), but as an MVP, we decide to implement a ML solution based only on text (the items title), and frame it as a **binary classification problem**.

We then build a dataset by querying from the Data Warehouse a sample of 1500 items from these two categories, with their titles (in lower case) and their categories (selected by the users when uploaded). This dataset can be found in the attached file `code/data.json`.

In `code/product_classifiers.ipynb` we will tackle the problem with two different approaches to assess the feasibility of the challenge.
