**Software and hardware specifications**
========================================

<table>
<thead>
<tr class="header">
<th><strong>Chapter number</strong></th>
<th><strong>Software required<br />
(with version)</strong></th>
<th><strong>Hardware specifications</strong></th>
<th><strong>OS required</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="2">1-12</td>
<td>Python 3.8</td>
<td rowspan="2">x86/AMD64 system</td>
<td rowspan="2">Windows,<br />
any Linux distro,<br />
or macOS</td>
</tr>
<tr>
<td>Any modern web browser, <br />such as Firefox, Edge, Safari, <br />or Chrome (recommended) </td>
</tr>
</tbody>
</table>

**\*Note**: The code in this book is in the form of python notebooks, and can be executed in Google Colaboratory. If you wish to execute these on your local machine, the (Python) package requirements are mentioned in the following section.

**Package specifications**
==========================

| **Package required**      | **Version**       | **Installation command (pip)** |
|---------------------------|-------------------|--------------------------------|
| Transformers              | 4.1.1 or higher   | `pip install transformer`      |
| genism                    | 3.8.3 or higher   | `pip install genism`       |
| TensorFlow                | 2.4.0 or higher  | `pip install tensorflow`            |
| NumPy                     | 1.19.5 or higher   | `pip install numpy`            |
| SciPy                     | 1.6.0 or higher   | `pip install scipy`           |
| pandas                    | 1.2.0 or higher   | `pip install pandas`           |
| Matplotlib                | 3.3.3 or higher   | `pip install matplotlib`       |
| scikit-learn              | 0.24.0 or higher  | `pip install scikit-learn`     |
| toposort                  | 1.6.0 or higher  | `pip install toposort`             |
| Sentencepiece             | 0.1.94 or higher | `pip install sentencepiece`             |
| trax                      | 1.3.7 or higher   | `pip install trax`  |
| Allennlp                  | 1.0.0 or higher   | `pip install allennlp`        |
| Allennlp-models           | 1.0.0 or higher   | `pip install allennlp-models`  |
| Farm-haystack             | 0.6.0 or higher   | `pip install farm-haystack`        |
| Torch                     | 1.6.0+cu101 or higher   | `pip install torch==1.6.0+cu101`  |

**\*Note**: This isn’t an exhaustive list of all the packages required to run the codes in this book, but only the essential and most commonly used packages in the book. You will likely encounter some more required packages as you read through the book, which you can install using `pip` or `conda`.
