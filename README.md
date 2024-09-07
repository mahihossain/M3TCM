# M3TCM

## Paper
https://aclanthology.org/2024.lrec-main.949/

## Getting Started

### Installation

Install necessary libraries with the help of `requirements.txt`.

### Dataset
Download the full dataset from the [Official Repo](https://github.com/uccollab/AnnoMI). We have used the full dataset(AnnoMI-full.csv) for our experiments.

### Basic Stattistic Inferences
For basic statistic inferences look at `stat_notebook.ipynb`.

### Data Preprocessing
The preprocessing notebooks are marked as `presprocessing_*.ipynb`, `*_preprocessing.ipynb`. or `*_preprocessing_*,ipynb` in their respective names.

### Example Process
For example if one want to get the `Hubert` embeddings, then one should at first download the whole dataset along with the audios from youtube. Then using `preprocessing_hubert.ipynb` notebook, one can get the embeddings.  

## License

Copyright 2024 Sayed Muddashir Hossain

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

- The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

- THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
