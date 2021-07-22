# Dustim-Toolkit

A Web-based Tool similar to https://pinetools.com/c-images/ website for generating Image gradients,
histogram, edge detection, corner detection, image pyramids, Fourier transforms
etc.. using open-cv.

- Tech Used : React Js, Djano, Open-CV, Python
- Deployment : Pending ...

The source code is **JavaScript and Python**.

## Project 
- Online image visualization and processing toolbox
- Goal: Need a website similar to https://pinetools.com/c-images/ but not with identical layout.

## Features
 1. Edge detection with different variant canny, sobel and others with adjustable parameters
Ref. https://scikit-image.org/docs/dev/auto_examples/edges/plot_edge_filter.html
http://airccse.org/journal/jcsit/1211csit20.pdf
2. Fouier transform and inverse fourier transform of the image
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_transf
orms/py_fourier_transform/py_fourier_transform.html
3. Image pyramid generation
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_pyra
mids/py_pyramids.html
4. Image gradient
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_gradi
ents/py_gradients.html
5. Image histogram
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_histo
grams/py_table_of_contents_histograms/py_table_of_contents_histograms.html
6. Image segmentation
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_water
shed/py_watershed.html
7. Corner detection
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_feat
ures_harris/py_features_harris.html#harris-corners

All the image proceeding should have adjustable parameters similar to
https://pinetools.com/c-images/ with download option. All the pages will have similar layout, the
backend might be python with appropropriate packages. The communication with the server
might be through a json object. The codes should be modular so that they can be later
integrated with more functionality. The developer can change the layout according to his choice
to make it more beautiful.

#### Show some :heart: and star the repo to support the project

## Installation
To install, simply clone this repository & run the following command  `yarn` or `npm install`, this will install all the dependencies for you.

## Running Project
To run this project locally, run the following command  `yarn start` or `npm start`, this will start a local instance of the application & you will be able to run the app in your browser at this url http://localhost:3000/.

## Some Screen Shots :

#### 1. Desktop View :
<img height="480px" src="https://user-images.githubusercontent.com/49696449/126699932-99e0961d-9db7-4432-a580-4d7c03a2db27.jpg">
<img height="480px" src="https://user-images.githubusercontent.com/49696449/126699946-f139d502-543e-40db-90f1-3304ca6697a3.jpg">
<img height="480px" src="https://user-images.githubusercontent.com/49696449/126699940-ead1bd05-c0bf-4a50-b5b4-8e9844fdf6f2.jpg">

#### 2. Mobile View :
<img height="480px" src="https://user-images.githubusercontent.com/49696449/126699958-02588261-d218-4b3b-8417-c0f4dcdfa5c4.jpg">

### 3. Design :
<img height="480px" src="https://user-images.githubusercontent.com/49696449/126700473-9393d732-a23c-4d46-999f-0b9bcdb25e07.jpg">


### Requirements / Getting started :

---------------------------------------------------------------------------------------------------------------------------------------
                                                          Python Part


- Download Python from : https://www.python.org/downloads/
- Python Version - 3.7.3 (Also Check the option -Add Python to Path)
- open command prompt and install the following packages
- Example :- pip install Django==3.0.2
- Django==3.0.2
- django-clear-cache==0.3
- django-cors-headers==3.5.0
- djangorestframework==3.12.1
- matplotlib==3.1.0
- opencv-python==4.2.0.32
- Pillow==7.2.0
- requests==2.22.0
- scikit-image==0.15.0
- scikit-learn==0.21.2
- scipy==1.5.3
- urllib3==1.24.2
- numpy==1.16.4
- CairoSVG==2.4.2
- bitarray==0.9.3 

- Install uniconvertor-2.0rc4-win64_headless.msi,
- Find the "dll" sub-directory under the UniConverter installation path.(In my case, C:\Program Files\UniConvertor-2.0rc4\dlls)
- Add this "dll" path to the system path.

- open the root of the project (In my case, D:\Django\dustim>)
- run the following commands :
- 1> python manage.py makemigrations
- 2> python manage.py migrate
- 3> python manage.py createsuperuser (remember username and password for admin login)
- 4> python manage.py makemigrations
- 5> python manage.py migrate --run-syncdb

- finally For running the server :- python manage.py runserver
- go to http://127.0.0.1:8000/admin/   and login with the above username and password here you can check all the data



--------------------------------------------------------------------------------------------------------------------------------------------------

                                                                       React Part

- 1. Install Node from https://nodejs.org/en/    (version = v14.5.0)
- To check version ( node -v)
- After Installation Add this to path (In my case, C:\Users\HP\AppData\Roaming\npm )

- 2. Install following packages 
- "@material-ui/core": "^4.11.0",
- "@material-ui/icons": "^4.9.1",
- "@testing-library/jest-dom": "^4.2.4",
- "@testing-library/react": "^9.5.0",
- "@testing-library/user-event": "^7.2.1",
- "axios": "^0.20.0",
- "react": "^16.13.1",
- "react-dom": "^16.13.1",
- "react-image-comparison-slider": "^1.8.4",
- "react-images-upload": "^1.2.8",
- "react-router-dom": "^5.2.0",
- "react-scripts": "^3.4.4",
- "react-zoom-pan-pinch": "^1.6.1"

- Example :- npm install axios@0.20.0
- i.e.   npm install <package-name>@<version>

- For running the server :- npm start   (In the root Directory, In my case , D:\React_JS\image-toolkit)

### :heart: Found this project useful?

If you found this project useful, then please consider giving it a :star: on Github and sharing it with your friends via social media.

# Pull Requests

I welcome and encourage all pull requests. It usually will take me within 24-48 hours to respond to any issue or request. Here are some basic rules to follow to ensure timely addition of your request:

1.  Match the document style as closely as possible.
2.  Please keep PR titles easy to read and descriptive of changes, this will make them easier to merge :)
3.  Pull requests _must_ be made against `master` branch for this particular repository.
4.  Make sure you follow the set standard as all other projects in this repo do
5.  Have fun!


<p align="center">
  <b><i>Let's connect! Find me on the web.</i></b>

[<img height="30" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />][twitter]
[<img height="30" src="https://img.shields.io/badge/linkedin-blue.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]
[<img height="30" src = "https://img.shields.io/badge/Facebook-036be4.svg?&style=for-the-badge&logo=facebook&logoColor=white">][Facebook]
[<img height="30" src = "https://img.shields.io/badge/instagram-c14438?&style=for-the-badge&logo=instagram&logoColor=white">][instagram]
<br />
<hr />

[twitter]: https://twitter.com/DalpatDc
[linkedin]: https://www.linkedin.com/in/dalpat-i-b5b451166/
[instagram]: https://www.instagram.com/dalpat_chaudhary__/
[Facebook]: https://www.facebook.com/dalpatchaudhary.blogspot.in/

If you have any Queries or Suggestions, feel free to reach out to me.
<h3 align="center">Show some &nbsp;❤️&nbsp; by starring some of the repositories!</h3>
