# Movie-Recommender-System
It is the Web Base Movie Recommender Engine which Implement Collaborative Filtering By matrix factorizations algorithm.

### Screenshot

###### Home page
![home](https://user-images.githubusercontent.com/20842692/45380125-941d7500-b61f-11e8-852d-c09e9586b35b.png)

###### Recommendation page
![recom](https://user-images.githubusercontent.com/20842692/45380167-b57e6100-b61f-11e8-8ec0-e07c26daa4a3.jpg)

###### Rating page
![rate](https://user-images.githubusercontent.com/20842692/45380186-be6f3280-b61f-11e8-8ad6-8b967d1cba1a.png)

### Technologies Used

#### Web Technologies
Html , Css , JavaScript , Bootstrap , Django

#### Machine Learning Library In Python3
numpy , pandas , scipy

#### Database
sqlite

##### Requirements
```
python 3.6

pip3

virtualenv
```
##### Setup to run

Extract zip file in your computer

Open terminal/cmd promt

Goto that Path

Example

```
cd ~/Destop/Movie-Recommender-System
```
Create a new virtual environment on that directory

```
virtualenv .
```

Activate Your Virtual Environment

for Linux
```
source bin/activate
```
for Windows
```
cd Scripts
then
activate
```
Downloading requirements

```
pip install -r requirements.txt
```
It will install all requirements.

### Creating Local Server

goto src directory example

```
cd ../Movie-Recommender-System/src
```
To run
```
python manage.py runserver
```
Now open your browser go to this address
```
http://127.0.0.1:8000
```
