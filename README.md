<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/DN_LogoDark.png" width="600">
    <img src="./assets/DN_LogoLight.png" width="600">
  </picture>
</p>

---

<div align="center">
A Python-based image editor made by David Norman Díaz Estrada<br>
  https://www.linkedin.com/in/dnde7/
</div>


------------------
**Color Mapping:**<br/>
------------------
The Color Mapping filter allows to apply any 8-color palette to an input image.
The current version has the following features:
<ul>
  <li>Edit and save any custom palette to the database.</li>
  <li>Palette generation based on a linear gradient between two colors.</li>
  <li>Palette extraction from any image using the k-means algorithm (tones from image).</li>
  <li>Color mapping modes: Fuzzy, Euclidean, and Light-based.</li>
  <li>The Fuzzy mode allows the user to adjust the "weight" of each color during mapping by moving the sliders.</li>
</ul>

Here is an example of color Mapping using a photo I took in Oslo:
<img src="readmeFiles/DN_app_01.png" >

These are some other examples with diverse palettes:
<img src="readmeFiles/examples_paletteMapping.png" >

------------------
**Pixelate Triangles:**<br/>
------------------
This filter pixelates an image with triangle shapes:
<ul>
  <li>The size slider controls the triangle dimensions.</li>
  <li>The Flip X option alternates the pattern by columns.</li>
  <li>The Flip Y option alternates the pattern by rows.</li>
</ul>

<img src="readmeFiles/triangleFilter.png" >

Here are some examples of different pixelation levels:
<img src="readmeFiles/triangleFilterExamples.png" >

------------------
**Demo Video:**<br/>
------------------
See the demo video: https://youtu.be/Vg87ZTrkO_c

[![Watch the video](https://img.youtube.com/vi/Vg87ZTrkO_c/hqdefault.jpg)](https://www.youtube.com/embed/Vg87ZTrkO_c)



------------------
**Installation:**<br/>
------------------
DN Image Editor requires the following dependencies: OpenCV, Scikit-learn, NumPy, Matplotlib, Tkinter, CustomTkinter, and Pillow.

First, clone this repo, you can do:
```
git clone https://github.com/DavidDZ7/DNimageEditor.git
```
Then, go to Anaconda prompt and navigate to the folder repo and proceed as follows:
```
conda create --name DNimageEditor python=3.7.7
conda activate DNimageEditor
pip install -r requirements.txt
```
Your environment is now ready, you can launch DN Image Editor by running:
```
python GUI_DN_Image_Editor.py
```


