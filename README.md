# StackoverFlow-Survey-Analysing-
It is just a fun project that i'm doing it just for fun that i am analysing 2023 stackoverflow survey and scrap what it is interesting for me with pandas.
# Stack overflow survey 2023 dataset link:
https://survey.stackoverflow.co/2023
# Virtual environment:
### I'm runnig this project on a local jupyterlab server with virtual environment that i will put step by step how to create a virtual environment if u are basic so follow process on your computer terminal.
### !!!these commands are on windows if it didn't work u can search if u are runnig it in another OS system:
## TO CREATE DIRECTORY:

mkdir (name of directory)

## TO CHANGE DIRECTORY:

cd (name of directory)


## TO CREATE VENV IN DIRECTORY:


python -m venv (name of venv file for example :venv)



## NOW YOU HAVE TO ACTIVATE IT TO USE:


(name of venv file for example:venv)\Scripts\activate

deavtivate(for quit venv envirement)


## NOW YOU ARE IN VENV ENVIRONMENT AND CAN DO ANYTHING U WANT:)

FOR EXAMPLE:


pip install requests(or any library u need)


### U CAN ALSO ADD EVERY LIBRARY OR ANYTHING THAT MAY BE CHANGE IN FUTURE AND USE IT U CAN CREATE A TEXT FILE THAT CAN BE UPDATED THAT INVOLVES YOUR LAST FUTURES U WANNA ADD TO VENV THAT ITS COMMON NAME THAT PLACED ON IT IS requirments.txt


### YOU CAN COPY YOUR LIBRARIES AND DATAS IN REQUIRMENTS.TXT WITH COMMAND:


pip freeze > requirments.txt

### AND AFTER U WANNA ADD THE TEXT FILE IN YOUR VENV TO UPLOAD IT:


pip install -r requirments.txt 


## For installing jupterlab or notebook module just need to run this bash:
pip install jupyter lab

## NOW For our purpose of building venv module we just need these steps after you bulid it once:

1. cd (path of directory of venv that u had been created)
2. venv/Scripts/activate
3. jupyter lab
4. ### Congratulation Now u will be direct to a local host server in browser and can have your jupyter IDLE there.

