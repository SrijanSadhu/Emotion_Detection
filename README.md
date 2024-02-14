This is a machine learning project, where the machine is trained to identify the emotions of the faces detected by the web camera of the PC.

**How to execute:**

1. Download the dataset from https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset
2. Delete the 'Images' folder inside the main folder and change the name of 'validate' folder to 'test'. 
3. To execute the project first download the whole project and run it in an IDE where the web camera of your PC can be accessed.
4. Open the terminal window of the IDE, and execute the requirements.txt file.
This can be done using the command: pip install -r requirements.txt
5. Execute the trainmodel.ipynb file. Execute the code snippets one-by-one. The code snippet which will train the machine, has 100 epochs. You can stop the training when you get a satisfactory accuracy(>80%), by pausing the execution of the training code snippet and executing the next one.
6. After executing all the code snippets from the above file, open the terminal and execute the realtimedetection.py file.
This can be done using command: python realtimedetection.py
