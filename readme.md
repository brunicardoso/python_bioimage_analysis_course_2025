# Fundamentos de Análise de Imagens de Microscopia em Python
# Fundamentals of microscopy image analysis in Python

## About
This repository contains materials for the course "Fundamentos de Análise de Imagens de Microscopia em Python" taught by Prof. Alexandre Bruni-Cardoso for graduate students at the University of São Paulo (USP).

The course is designed for graduate students who want to learn computational tools for microscopy image analysis, with a focus on Python. It covers fundamental concepts, image processing, segmentation, and data visualization.

## Course Objectives
To enable students to use computational tools, focusing on Python, for microscopy image analysis, addressing fundamental concepts, image processing, segmentation, and data visualization.

## Prerequisites
- Personal laptop with minimum specifications: 4GB RAM, 10GB free storage, modern processor (e.g., Intel i5 or better), and internet connection
- Active Google account (for Google Colab)
- Pre-installation of FIJI/ImageJ
- Preferably, students should already use or plan to use bioimage analysis in their projects

## Course Schedule

### Day 1: Basic Concepts and Introduction to Python for Images
- Practical introduction based on active learning concepts
- Representing images as numbers: manipulation with NumPy and Scikit-image in Google Colab
- Image structure and characteristics (pixels, shape, channels)
- Python as a calculation tool, variables, functions, and packages
- Extracting numerical information: generating tables and histograms
- Image processing, segmentation, and measurements of morphology and fluorescence intensity

**Materials:**
(notebooks day1_1 to day2_4 can be run directly in Google Colab.
 The remaining notebooks should be run locally after the installation of packages listed in bioimage_analyst_env.yml and bia_bob_environment.yml 
 or in Google Colab after adjusting (Napari won't run in Colab))

- `day1_1_Prepping_1_Google_Colab.pptx` - Introduction to Google Colab
- `day1_1_instant_gratification.ipynb` - Quick start with Python for image analysis
- `day1_2_course_overview.pptx` - Course structure and expectations
- `day1_2_python_basics_operations_variables.ipynb` - Python fundamentals
- `day1_3_pixels_numbers_LUT.ipynb` - Understanding image data
- `day1_4_functions_and_packages.ipynb` - Working with Python functions and libraries
- `day1_bioimage_analysis_workflow.excalidraw` - Visual guide to the bioimage analysis process
- `day1_3_Prepping_1_Google_Colab_Mounting_drive.pptx` - Connecting Colab to Google Drive
- `day1_5_image_processing_segmentation_quantification.ipynb` - Basic image analysis workflow

### Day 2: Deep Learning Tools for Segmentation and Data Visualization
- Introduction to Deep Learning applied to cell segmentation: using Stardist and Cellpose
- Setting up local Python environments with Miniconda
- Automating segmentation and image analysis
- Plotting simple graphs (fluorescence, morphology) with Matplotlib
- Introduction to Superplots with examples from scientific publications

**Materials:**
- `day2_deep_learning_very_basic.excalidraw` - Visual introduction to deep learning concepts
- `day2_1_segmentation_with_DeepLearning_based_tools.ipynb` - Using Cellpose and Stardist
- `day2_2_best_practices_notebook.ipynb` - Recommended practices for scientific computing
- `day2_1_installing_miniconda_and_environment_management.pptx` - Setting up local environments
- `day2_3_loops_python.ipynb` - Iteration and automation in Python
- `day2_4_automation_segmentation_image_to_numbers.ipynb` - Batch processing of images
- `day2_5_superplots-tutorial.ipynb` - Advanced data visualization for publication

### Day 3: Cellpose Training and AI Tools
- Training custom models with Cellpose
- Exploring AI tools (LLMs and chats) applied to bioimage analysis
- Responsibilities and best practices for using AI to generate code
- Implementing tools like Gemini and Agentic AI for bioimage analysis workflows
- Final project

**Materials:**
- `day3_1_cellpose_gui_train_your_own_model.pptx` - Cellpose model training guide
- `day3_1_run_your_own_cellpose_model.ipynb` - Hands-on custom model training
- `day3_2_AI_assisted_programming.pptx` - Introduction to AI-assisted code generation
- `day3_2_BiaBob_AI_assistant_for_bioimage_analysis.ipynb` - Working with specialized AI tools
- `day3_3_exercise_protein_translocation.pptx` - Practical exercise
- `day3_4_Wrapping_up.pptx` - Course summary and next steps

## Data Files
The repository includes various sample images for practical exercises:
- `hela-cells-8bit.tif`
- `blobs.tif`
- `data_for_superplot_JCB_paper.csv`
- Various instructional videos (e.g., `luts_brightness.mp4`, `simple_microscope.mp4`)

The images used in the exercises are downloaded directly from the internet, form imagej sample images ( https://imagej.net/ij/images/ ) or from the public repository at https://bbbc.broadinstitute.org/
## Environment Files for
Windows: 
- `bia_bob_environment.yml` - Environment configuration for BiaBob AI assistant
- `bioimage_analyst_env.yml` - General environment for bioimage analysis
Mac:
- `bia_bob_macb.yml` - Environment configuration for BiaBob AI assistant
-`bioimage_analyst.yml`- General environment for bioimage analysis

## Methodology
The course combines lectures with practical activities in Jupyter Notebooks and exercises based on real cases.

## Evaluation
Completion of practical exercises and submission of a final project.

## Usage
1. Clone this repository or download the files
2. Set up your environment following instructions in `day2_1_installing_miniconda_and_environment_management.pptx`
3. Open notebooks in Jupyter or Google Colab
4. Follow the course materials in the order listed above

## Contact
For questions about this course ant the material, please contact Prof. Alexandre Bruni Cardoso at brunicar@iq.usp.br 

## Most of the material in the course are explored in video tutorials in the YouTube channel https://www.youtube.com/channel/UCbJAU7N9FYvwkdgSwD_1S4Q

---

© 2025 Alexandre Bruni Cardoso, University of São Paulo
