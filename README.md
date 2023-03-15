# Movie-Recommendation-System-Web-Application-Project
Building a Movie Recommendation System web application using Django framework and Recommendation technique called Collaborative Filtering 
- Matrix Factorization Algorithm
The recommendation based on the underlying idea that is if two persons both liked certian common movies,then the movies that one person has liked that the other person has not yet watched can be recommended to him.  

### Screenshot

###### Home page
![home](https://user-images.githubusercontent.com/20842692/45380125-941d7500-b61f-11e8-852d-c09e9586b35b.png)

###### Recommendation page
![recom](https://user-images.githubusercontent.com/20842692/45380167-b57e6100-b61f-11e8-8ec0-e07c26daa4a3.jpg)

###### Rating page
![rate](https://user-images.githubusercontent.com/20842692/45380186-be6f3280-b61f-11e8-8ad6-8b967d1cba1a.png)

### Technologies Used
#### Web Technologies
- Python
- HTML 
- CSS
- JavaScript
- Bootstrap 

#### Python Packages 
- Django
- Numpy
- Pandas 
- Scipy

#### Database
SQLite

##### Requirements
```
python 3.9.5
pip 21.1.1
virtualenv
```

##### Setup to run

- Download zip file to your local machine
- Extract the zip file
- Open terminal/cmd promt
- Goto that Path

Example

```
cd ~/Desktop/Movie-Recommender-System-Web-Application-master
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

Command line to install all dependencies
```
pip install -r requirements.txt
```
### Creating Local Server

Go to MovieRecommendationApp directory
```
cd ../Movie-Recommender-System/MovieRecommendationApp
```

Command line to run the program
```
python manage.py migrate
python manage.py runserver
```

Now open the browser and go to this address
