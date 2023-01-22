# Sign_detection
An AI sign-detection model made through tensorflow working models. Encorporated my images into the model to detect my hand signs.

Basic sign-detection project using the tensorflow object detection API to leverage the model to detect and identify different hand-signs. Using these set of notebooks you get a Walk through to replicate and create your own sign-detection model by using your images and leverage the model accordingly.



![Untitled](https://user-images.githubusercontent.com/91323828/213932788-1e5fcc14-e380-4cd1-af8e-70b1e81f10d7.png)

If you wish to replicate this project you can start by replicating or cloning my repository : https://github.com/SrivathsG/Sign_detection

<h3> 1st Step: </h3>
Make your local virtual environment
<pre> python -m venv sgd </pre>
<h3> 2nd Step: </h3>
Activate your environment.
<pre> .\sgd\scripts\activate </pre>
<h3> 3rd Step: </h3>
Download your dependencies
<pre>pip install ipykernel
python -m ipykernel install --user --name=sgd </pre>
<h3> 4th Step: </h3>
Collect your images using the notebook : <a href="https://github.com/SrivathsG/Sign_detection/blob/main/1.%20Image%20Collection.ipynb"> Image collection.ipynb</a>

You can also collect your images traditionally using your camera and store them in the directory and files specified in the notebook
since these file paths will be used later to create TF records and several other things.

<h3> 5th Step: </h3>
Next after collecting all the images it is necessary to crop and label the images.
You can refer to the GUI toolkit from the repository: https://github.com/tzutalin/labelImg

<h3> 6th Step: </h3>
Make sure to divide your labelled images into two different sets: 'Train' and 'Test' datasets in the images folder

<h3> Now that you have successfully collected your images its time to Train the model!!</h3>
You can then follow along the commands provided in the:
<a href="https://github.com/SrivathsG/Sign_detection/blob/main/2.%20Training%20and%20Detection1.ipynb">Training.ipynb</a>

<h5> First requirement is download the required Object_detection model from the tensorflow model zoo from the following repository:
  research/object_detection/g3doc/tf2_detection_zoo.md



