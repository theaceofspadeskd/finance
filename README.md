# finance

Website, builded on Flask, via which users can buy and sell stocks

All requirements and specification can be viewed here: https://cs50.harvard.edu/x/2022/psets/9/finance/

Run in Docker:

1. Pull image
 ```
 docker pull theaceofspadeskd/finance:v1 
 ```
2. Run container  
 ```
 docker run -p 8000:8000 theaceofspadeskd/finance:v1
 ```   
 

Installation:

1. Download this project
    ```
    git clone https://github.com/theaceofspadeskd/finance.git
    ```
2. Install all necessary dependencies
    ```
    pip install -r requirements.txt
    ```
3. Run project:
    ```
    flask run
    ```
