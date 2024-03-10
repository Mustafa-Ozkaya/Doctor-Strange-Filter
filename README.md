![Banne](https://wallpapers.com/images/featured/doctor-strange-6es4yutxrbl0nas9.jpg)

# Doctor Strange Filter with Python

This project was developed to test my computer vision skills. It was created using the Mediapipe and OpenCV libraries, along with the Python programming language. As the name suggests, I attempted to mimic the magic circles that appear on the palms of the popular MARVEL hero Dr. Strange when he casts a spell.

To summarize the working logic of the project, the script first detects hand gestures from the device's camera and then calculates the midpoint of the palms and the openness of the palms with these points. If your hand is open enough, a mask (the filter itself) is created using the previously provided images and pasted onto the calculated midpoint.

Of course, this was a very simplified explanation. There are many things to learn about perspective, rotating image objects, and creating transparent objects during this project. I hope this project will help you understand these topics.

## Folder Structure

```
.
├── Models                    # Models to be used when creating the filter
|   ├── Inner Circles         # Circle models to be found on the inner side 
|   └── Outer Circles         # Circle models to be found on the outer side 
├── functions.py              
├── main.py                    
├── requirements.txt                   
└── README.md
```

## Setup

1. Install Python (I used Python version 3.10): `https://www.python.org/`
2. Install requirements : `pip install -r requirements.txt`
3. Run main.py script : `python main.py`

## Some of Photos

<p align="center">
  <img src="https://e0.pxfuel.com/wallpapers/144/187/desktop-wallpaper-dr-strange-top-65-best-dr-strange-background-doctor-strange-neon.jpg" width="250" />
  <img src="https://c4.wallpaperflare.com/wallpaper/365/584/63/movie-doctor-strange-benedict-cumberbatch-marvel-comics-wallpaper-preview.jpg" width="250" /> 
  <img src="https://wallpapercave.com/wp/wp3978705.jpg" width="250" />
</p>

</p>

***
<h3 align="center"> Nurettin Mustafa Özkaya </h3>
<p align="center">
      https://linktr.ee/mustafaaozk
</p>
