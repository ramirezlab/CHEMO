# Collaborative Chemoinformatics Open Platform (CHEMO)

## INTRODUCTION
### Drug Design and Modeling: Exploring the Intersection of Data Science and Drug Discovery
Drug design and modeling is an area that continues to expand in significance in the field of drug discovery. Specifically, the science of computer-aided drug design (CADD) has proven critical to discovering, designing, or optimizing small molecules that have the potential to become viable medicinal treatments.

As CADD continues to evolve, data science has come to play a vital role in advancing drug discovery. The application of data science techniques such as machine learning and data mining have increased the efficiency and accuracy of the process.

The Data Science for Drug Design (DS4DD) program aims to provide a comprehensive and thorough understanding of CADD fundamentals, with an emphasis on incorporating key data science techniques throughout. The course covers a wide array of content, ranging from the foundational elements of Python programming, to ligand-based and structure-based drug design, as well as virtual screening.

DS4DD is an exceptional resource for students, researchers, and professionals seeking to enhance their knowledge of CADD, and those interested in understanding the critical role that data science plays in drug discovery. By enrolling in this course, participants can expect to gain a deeper understanding of the exciting developments in this rapidly-growing field.

## Table of contents
- **Part one**. Introduction to Python
  - Variables, data types, data structures, file manipulation, flow control structures, functions...
  - *Practice*: Expression of genetic material
  - *Practice*: Proteins and amino acids

- **Part two**. DataFrames and data visualization
  - **2.1** Introduction to manipulating advanced data structures
      - `numpy` and `pandas` libraries
      - Database cleaning and filtering 
      - *Practice*: Compound data acquisition: ChEMBL
      
  - **2.2** Introduction to data visualization
      - `matplotlib` and `seaborn` libraries
        - Lineplots, pie plots, horizontal bar plots, vertical bar plots, histograms, radar plots, ...
      - *Practice*: Molecular filtering: ADME and lead-likeness criteria
      - *Practice*: Ligand-based screening: Compound similarity and compound clustering
- **Part three**. Machine learning
  - **3.1** Introduction to Machine Learning
  - **3.2** Ligand classification model
       
## Objetive
The aim of this course is to teach essential concepts and skills in drug design and modeling. The course is designed to cater to a wide range of students, from novice to advanced, covering multiple topics, such as an introduction to Python, data manipulation and visualization, structure-based and ligand-based drug design, and virtual screening. The curriculum is modular to let instructors customize the material according to their needs and teaching methods.

### Why take this course?
There are several reasons for taking this course. Firstly, it provides a strong foundation in computer-aided drug design (CADD), which is an increasingly vital field in drug discovery. Secondly, the course is comprehensively designed to cover from basics to advanced topics, making it suitable for students at all levels. Finally, the flexibility of the curriculum enables it to be tailored according to one's learning needs.

### Who is this course for?

This course is suitable for undergraduate and graduate students who want to delve into computer-aided drug design (CADD) and apply the principles of data science to the field of drug design. It is also fitting for researchers, professionals, and scientists who want to enrich their understanding of the concepts and techniques of CADD.

### What do you need?

You can use our notebooks by either cloning the repository or downloading it from the website.

1. Option 1: Downloading it as a zip archive and unzipping it.

   Option 2: Cloning the repository to your computer using the `git` package.
   
```console
git clone https://github.com/ramirezlab/DS-for-DD.git
```

2. We recommend using the Anaconda software for a clean installation where you can create an environment and install all the required packages.

Install Anaconda: [https://docs.anaconda.com/anaconda/install/](https://docs.anaconda.com/anaconda/install/)

3. Use the package management system conda to create an environment (chemo). We provide an environment file (yml file) containing all required packages. Once Anaconda is installed, you can initiate the command line to create the environment and install the requirements using the following code:

```console
conda env create -file=requisites.yml
```

The `requisites.yml` file must be in the same directory where the code is executed.

4.  Activate the conda environment
```console
conda activate chemo
```
Now, you can work within the conda environment.

5. Start the Jupyter notebook.
```console
jupyter notebook
```
>You can now get started with your first notebook. Enjoy!

## Contact


## Licence
This work is licensed under the MIT License

## Citation

## Special Thanks


