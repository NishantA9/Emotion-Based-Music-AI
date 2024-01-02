# emotion-based-music-ai by Innov8 Developers

Hello and Welcome to Emotion Based Music AI. 

-------------------------------------------------------------------------------------------------------------------

To run the app please follow the Instructions given below.

1) You need to Install Python (Version 3.11.5 or bellow) 
Note. You need to download the above version only to run our app, as we use Tensor flow library the current python version doesn't support the tensor flow. So it's recommended to use the version mentioned. Here is the link to download this version: 
https://www.python.org/downloads/release/python-3115/

2) Once Python is installed. Run the python command terminal and then install the following libraries.

Install flask: pip install Flask

Install numpy: pip install numpy

Install open-cv: pip install opencv-python

Install Tensor-Flow: pip install tensorflow

Install Keras: pip install keras

3) Once the libraries are install, Make sure to extract the Zip file of our project, then go to the extracted folder, and run App.py. Also if it gives any error while running then in the project folder, Right click and open the terminal. Then run the command python app.py.

Note. if you face any issues regarding flask, this may be because of the directory being changed, make sure to change the template folder path to the path where you extracted and installed the project. To fix this, open App.py code in any of Code Editor (Visual Studio Code) and edit the below line.

app = Flask(__name__, template_folder="C:\\Users\\firee\\OneDrive\\Desktop\\Personal\\Nishant Files\\Nishant Files\\Nishant Personal\\Master's UNCC Courses\\SEM 1\\SSDI\\SSDI PROJECT\\B.E SEM8 proj\\emotion-based-music-ai-main\\emotion-based-music-ai-main\\templates")

Note. Here change the path of template_folder="", and add your path. then save and run the app, this will fix the issue of running the code.


4) Once the terminal starts running, there will be a server link in the terminal, Press ctrl and click on that server link. This will take you to our project website. And done, this will start our project and then you can select the language and the singer and then the camera will detect your emotion and will recommend you the song.

Note. In the terminal there will be a specific line like this (Running on http://127.0.0.1:5000) make sure to click on it to go to our website.

-----------------------------------------------------------------------------------------------------------------------

About Innov8 Developers.

We are a dynamic team of five individuals at Innov8 Developers, driven by a shared passion for innovation and development. Our diverse skills converge to create a powerhouse of creativity and technical expertise. Committed to excellence, we tackle challenges collaboratively, turning ideas into impactful projects. Join us on this exciting journey where we innovate, inspire, and make a lasting impact. Innov8 Developers – where ideas come to life!

Our Team Members:

Vedant Patni
Nishant Suresh Acharekar
KSNSS Padmini
Nishan Dhakal
Harsha Peteti

//-----------------------------//




