<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/Gradio_main.png"/>
<br><br>


# Building Interactive Web Apps with Gradio

This open-source Python tutorial will guide you in quickly building demos or web applications with Gradio. You'll start by setting up your Python environment and end with deploying interactive apps. Learn to make interfaces for text and images, improve user experience with layout customization, and manage complex interactions.

The course will also cover processing remote sensing data with Gradio and GDAL for tasks like image enhancement and slope analysis. You'll discover how to create interactive maps with Gradio and Foliumap, enabling dynamic geospatial data visualization.

Designed to equip you with the skills to integrate machine learning models and deploy your apps on Hugging Face Spaces, the course includes practical examples, demos, and assignments. By completing the tutorial, you'll be able to build, deploy, and share interactive web applications confidently and efficiently.


<img src="https://huggingface.co/datasets/huggingface/documentation-images/resolve/main/gradio-guides/lcm-screenshot-3.gif" style="padding-bottom: 10px"><br><br>

### Comprehensive Installation Guide
#### 1. Setting Up Virtual Environment
To ensure compatibility and isolate dependencies, create a virtual environment named "`gradiotask`" or another name you prefer for this Gradio tutorial. This tutorial is built using **Python 3.10.6**. We recommend configuring a Python version **3.10 or above** for the best experience.

- Creating and Activating the Virtual Environment
 Use the following command to create a new environment with Python 3.10.6:
   ```bash
   conda create -n gradiotask python=3.10.6
   ```         
- To activate the virtual environment, use the following command:
    ```bash
    conda activate gradiotask
    ```
> Tips:
 > Remember to activate your virtual environment (`gradiotask`) before installing or running any packages related to this tutorial. Once you are finished, you can deactivate the environment by running `conda deactivate`. If necessary, you can remove the virtual environment with the command `conda env remove -n gradiotask`.

#### 2. Gradio Installation 
**Gradio** requires **Python 3.8 or higher**. Before you proceed, ensure you have Python installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).

We recommend installing Gradio using `pip`, which is included by default in Python. Run this in your terminal or command prompt:

```bash
pip install gradio
```
> Tips: 
 >Detailed installation instructions for all common operating systems <a href="https://www.gradio.app/main/guides/installing-gradio-in-a-virtual-environment">are provided here</a>. 

#### 3. Additional Libraries Installation

For running the demos and ensuring compatibility, you may need to install the following libraries with specific versions:

- **Pillow**: Version 9.2.0
- **pandas**: Version 1.5.0
- **GDAL**: Version 3.4.3
- **numpy**: Version 1.23.3
- **geopandas**: Version 0.11.1
- **Shapely**: Version 1.8.4
- **scikit-learn**: Version 1.1.2
- **joblib**: Version 1.2.0
- **openai**: Version 1.16.2
- **leafmap**: Version 0.29.1
- **Gradio**: Version 4.27.0

> Tips: To install these libraries, you can all use pip install command, 
Installing **GDAL** can sometimes be problematic due to its size and dependencies. We recommend installing GDAL locally to avoid potential issues with online installation. [Here](https://wheelhouse.openquake.org/v3/windows/py310/GDAL-3.4.3-cp310-cp310-win_amd64.whl) is the GDAL 3.4.3 installation packages for windows and python 3.10. If you need other version of GDAL, please ensure you download the version that matches your operating system and Python environment. <br><br>


### Learn from Demo

This tutorial is structured into six sections, each section is offering hands-on experience. Through 12 demo cases, you can learn how to build interactive web apps, from basic interfaces to complex machine learning integrations and geospatial visualizations, culminating in deploying on Hugging Face.

#### 1. Introduction to Gradio
##### Demo 1-1: Build Your First Gradio App

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo1-1.gif" alt="Demo Image" class="center-image"/>

##### DEMO 1-2: Display an Image

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo1-2.gif" alt="Demo Image" class="center-image"/>

#### 2. Interface Design and Interactive Components
##### DEMO 2-1: Interactive Multi-Component Gradio Interface

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo2-1.gif" alt="Demo Image" class="center-image"/>

##### DEMO 2-2: Diverse Data Display and File Interaction App

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo2-2.gif" alt="Demo Image" class="center-image"/>

#### 3. Working with Remote Sensing Data
##### DEMO 3-1: Remote Sensing Imagery Visulization

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo3-1.gif" alt="Demo Image" class="center-image"/>

##### DEMO 3-2: Geospatial Coordinate Conversion and Shapefile Generator App

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo3-2.gif" alt="Demo Image" class="center-image"/>

##### DEMO 3-3: DEM Visualization and Slope Analysis App

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo3-3.gif" alt="Demo Image" class="center-image"/>

#### 4. Application of Machine Learning Models
##### DEMO 4-1: Handwritten Digit Recognition App

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo4-1.gif" alt="Demo Image" class="center-image"/>

##### DEMO 4-2: ChatBot App Building with Gradio and Kimi

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo4-2.gif" alt="Demo Image" class="center-image"/>

#### 5. Building Interactive Maps Using Gradio and Folium.
##### DEMO 5-1: Interactive Map Generation Using Gradio and Leafmap

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo5-1.gif" alt="Demo Image" class="center-image"/>

##### DEMO 5-2: Geospatial COG and TIFF Viewer App

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/demo5-2.gif" alt="Demo Image" class="center-image"/>

#### 6. Deploy and Share Your Gradio App
##### DEMO 6-1: Deploying a Gradio App on Hugging Face 

<img src="https://dunazo.oss-cn-beijing.aliyuncs.com/blog/build)web_app_in_HF.gif"/>

To learn more about sharing your demo, read our dedicated guide on [sharing your Gradio application](https://www.gradio.app/guides/sharing-your-app).<br><br>


### Reference Material Related to Gradio

- [Website:https://gradio.app](https://gradio.app)
- [Documentation:https://gradio.app/docs/](https://gradio.app/docs/)
- [Guides:https://gradio.app/guides/](https://gradio.app/guides/)
- [Getting Started:https://gradio.app/getting_started/](https://gradio.app/getting_started/)
- [Hugging Face Spaces:https://huggingface.co/spaces](https://huggingface.co/spaces)


