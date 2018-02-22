# flask

## Running the Flask

1. Create a virtual environment on the command line using the following command:
```
conda create -n <place your env name here> python
```
  
  

2. Activate the virtual environment:
    - For Mac users:         ```source activate <place your env name here>```
    - For Windows users:       ```activate <place your env name here>```
   
   
   
3. Install flask on the virtual environment:
``` 
pip install flask
```
    
    
    
4. Install the systeminfo file from the [systeminfo GitHub repository](https://github.com/Eimg851/systeminfo.git)
    - or use the following command:
```
pip install git+https://github.com/Eimg851/systeminfo.git
```
 
 
 
5. Git clone the flask application to you machine:
```
git clone https://github.com/Eimg851/flask.git
```
  
  
  
6. Run the flask application:
``` 
python flask/dummyapp/run.py
```
  
  
  
7. Open a web browser and navigate to localhost:5000 to view the flask application running on a webserver. You should see the platform on which the flask application is running along with total, used and free storage. 

    
