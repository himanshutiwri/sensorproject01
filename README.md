## Machine learning Sensor Project

A Python-based web application that detects whether sensors are functioning normally or showing faults using Machine Learning techniques.

Built with Flask, Pandas, and Scikit-learn for backend processing and the prediction.

1. **Setup Virtual Environment**:
   - Open the terminal.
   - Install the virtual environment package if you haven't already
   - Create a virtual environment: `virtualenv venv`.
   - Activate the virtual environment:
    conda activate venv/


2. **Install Requirements**:
   - Install the requirements: `pip install -r requirements.txt`.

3. **Running the Project Locally**

1.Launch the Flask application:

python app.py

2.Open your browser and go to:

http://localhost:10000/
Example of the interface:-go to this image:[Screenshot 1](screenshots/Screenshot_2025-09-27_142720.png)

http://localhost:10000/train
Example of the interface:-go to this image:[Screenshot 2](screenshots/Screenshot_2025-09-27_143117.png)

http://localhost:10000/predict
Example of the interface:-go to this image:[Screenshot 3](screenshots/Screenshot_2025-09-27_142303.png)

   
4. **Let's Deploy it at Render.com**:
   -go to this website: https://dashboard.render.com/web
   -then click on new and choose web serivces
   -choose this :Build and deploy from a Git repository and click on next
   -then in settings : this will open [Screenshot 4 ](screenshots/Screenshot_2025-09-27_113600.png)


6. **So click on manual Deploy and select deploy with latest commit**
   -and wait 2-3 mint after that your website will be published.
   -https://sensorproject01-bfap.onrender.com/
   
   
[Screenshot 5 -prediction page](screenshots/Screenshot_2025-09-27_142303.png)


🚀 **Ready to Use**

You can now analyze sensor data, detect faults, and visualize result easily with this app.