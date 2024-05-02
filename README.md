# workshop-notebooks-dhnb2024

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/workshop-notebooks-dhnb2024/HEAD)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hibernator11/workshop-notebooks-dhnb2024)

<img src="images/dhnb.png" width="70%">

This project has been developed as part of the workshop "Reusing digital collections from GLAM Labs: a Jupyter Notebook approach" for the [DHNB 2024 conference](https://www.conftool.org/dhnb2024/sessions.php).

The coordinators of the workshop are:

- Gustavo Candela, University of Alicante, Spain
- Mirjam Cuper, National Library of the Netherlands
- Olga Holownia, International Internet Preservation Consortium
- Max Pedersen, Royal Danish Library, Denmark

## Digital collections
[Timarit.is](https://timarit.is/) is a collaborative project between the following institutions:

- National Library of the Faroe Islands
- National and Public Library of Greenland
- National and University Library of Iceland

The access is open to everyone and the material is made available by using the latest methods in information technology.

## Notebooks

This project contains the following Jupyter Notebooks:

- [yolo-example-cli.ipynb](https://nbviewer.org/github/hibernator11/workshop-notebooks-dhnb2024/blob/main/notebooks/yolo-example-cli.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hibernator11/workshop-notebooks-dhnb2024/blob/main/notebooks/yolo-example-cli.ipynb)
  

## Steps required for Colab

This steps are required to be able to run the notebooks in Google Colab, including the installation of the python packages and the download of the images from GitHub (or using the GitHub url):

- `!pip install opencv-python`
- `!pip install opencv-python-headless`
- `!pip install ultralytis==8.0.196`
- `!curl -O https://raw.githubusercontent.com/hibernator11/workshop-notebooks-dhnb2024/main/images/timarit/Sheep/20180107i1p11.jpg`
- `!yolo predict model=yolov8n.pt source='https://raw.githubusercontent.com/hibernator11/workshop-notebooks-dhnb2024/main/images/timarit/Sheep/20180107i1p11.jpg'`

## References

- [Timarit.is](https://timarit.is/)
- [GLAM Workbench](https://glam-workbench.net/)
- [International GLAM Labs Community](https://glamlabs.io/)
- Candela, G., Chambers, S., & Sherratt, T. (2023). An approach to assess the quality of Jupyter projects published by GLAM institutions. Journal of the Association for Information Science and Technology, 74(13), 1550–1564. https://doi.org/10.1002/asi.24835
