This is a machine learning project, where the machine is trained to identify the emotions of the faces detected by the web camera of the PC. The machine is trained using CNN and currently it has an accuracy of 67%.

**How to execute:**

1. To execute the project first download the whole project and run it in an IDE where the web camera of your PC can be accessed.
2. Open the terminal window of the IDE, and execute the requirements.txt file.
This can be done using the command: pip install -r requirements.txt
3. Currently the model is trained to an accuracy of 67%, which, to be honest, is a very low accuracy. So, to re-train the model, execute the trainmodel.ipynb file. Delete the emotiondetector.h5 and emotiondetector.json files. Execute the code snippets one-by-one. The code snippet which will train the machine, has 100 epochs. You can stop the training when you get a satisfactory accuracy(>80%), by pausing the execution of the training code snippet and executing the next one.
4. After executing all the code snippets from the above file, open the terminal and execute the realtimedetection.py file.
This can be done using command: python realtimedetection.py
