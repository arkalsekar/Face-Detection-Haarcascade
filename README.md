# Face Detection using OpenCV

The code uses Python and OpenCV and OpenCV Frontal Face Haarcascade to detect faces in images as well as live video footage. However, during this era of Advance Deep Learning Age and Robust Model Building, Haarcascade techniques are'nt that efficient but works just fine. All thanks to OpenCV and Adrian from PyImageSearch for this code. 

## Demo 
![](https://github.com/arkalsekar/Face-Detection-Haarcascade/blob/main/images/image_3.jpg?raw=true)

![](https://github.com/arkalsekar/Face-Detection-Haarcascade/blob/main/test/image_3.png?raw=true)


![](https://github.com/arkalsekar/Face-Detection-Haarcascade/blob/main/images/image_4.jpg?raw=true)

![](https://github.com/arkalsekar/Face-Detection-Haarcascade/blob/main/test/image_4.png?raw=true)



![](https://github.com/arkalsekar/Face-Detection-Haarcascade/blob/main/images/image_5.jpg?raw=true)

![](https://github.com/arkalsekar/Face-Detection-Haarcascade/blob/main/test/image_5.png?raw=true)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all the requirements.

```bash
pip install -r requirements.txt
```

## Usage
The Usage of this code is damn simple. 
<br>
Firstly, Either Download the Zip and Extract the Code or simply Clone the Repo using.

```bash
git clone https://github.com/arkalsekar/Face-Detection-Haarcascade
```
Once Clone the Repo, head on to the repository.
<br> 
Here you will find two code files, once is for images and other one is for video stream.

Here is how to run video stream face detection. 
```bash
python .\video_face_detector.py -c .\face_detector\haarcascade_frontalface_default.xml
```

Here is how to run image face detection. 
``` bash 
python .\haar_face_detector.py -i .\images\image_1.jpg -c .\face_detector\haarcascade_frontalface_default.xml
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
