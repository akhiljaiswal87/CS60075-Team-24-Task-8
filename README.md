![measeval-logo](C:\Users\SHRMO\Downloads\measeval-logo.jpg)

Open in colab : https://colab.research.google.com/drive/13FhVXgRn_3_lw7gjdk1ZeYzxtg1qYL4p?usp=sharing
# Introduction

Counts and measurements are an important part of scientific discourse. It is relatively easy to find measurements in text, but a bare measurement like "17 mg" is not informative. However, relatively little attention has been given to parsing and extracting these important semantic relations. This is challenging because the way scientists write can be ambiguous and inconsistent, and the location of this information relative to the measurement can vary greatly.

MeasEval is a new entity and semantic relation extraction task focused on finding counts and measurements, attributes of these quantities, and additional information including measured entities, properties, and measurement contexts.

# List of contributors

1. Akhil Jaiswal
2. Manasvi Sagarkar
3. Shreyas More
4. Ravi Pratap Singh
5. Sahil Jain

# Requirements

| Package       | Version |
| ------------- | ------- |
| sci-kit learn | 0.22.2  |
| spaCy         | 2.3.5   |
| NLTK          | 3.2.5   |
| pandas        | 1.1.5   |
| NumPy         | 1.19.5  |
| scaremoses    | 0.44.4  |
| tokenizers    | 0.10.1  |
| transformers  | 4.4.2   |
| argh          | 0.26.2  |
| pathtools     | 0.1.2   |
| watchdog      | 0.83    |



# Instructions to execute the code

1. Clone the repository.
2. Upload the file Group_24_Task_8.ipynb in google colab.
3. Run individual cells to see steps performed (all cells could also run at once).
4. The code also clones the measeval original repo for getting its training and testing data.
5. The code automatically installs all the necessary libraries when the cells are executed.
6. The first cell of transformer section sometimes needs to be run twice to install libraries 
7. The paths are written in such a way that it works well in colab.
8. At last output files for submission is downloaded in zip format.

# Results

![quantity_f1](E:\MTech II\Natural Language Processing\Assignment\quantity_f1.jpeg)

<img src="E:\MTech II\Natural Language Processing\Assignment\measuredentity_f1.jpeg" alt="measuredentity_f1" style="zoom:92%;" />

<img src="E:\MTech II\Natural Language Processing\Assignment\measuredproperty_f1.jpeg" alt="measuredproperty_f1" style="zoom:87%;" />

<img src="E:\MTech II\Natural Language Processing\Assignment\overall_f1.jpeg" alt="overall_f1" style="zoom:170%;" />

