# Functional Prototype: Hodor and Bran Services

## Hodor Service :-
Description: Hodor is a GoLang service. <br> GitHub Repository: [Hodor GitHub Repository](https://github.com/bhupenderyadav7424/hodr)

## Bran Service
Description: Bran is a Django service. <br>
GitHub Repository: [Bran GitHub Repository](https://github.com/bhupenderyadav7424/bran)

## Instructions to Run the Server and Test the API:
#### Hodor Service:
### 1. Clone the Repository: 
git clone https://github.com/bhupenderyadav7424/hodr.git <br>
cd hodr

### 2. Build the Docker Image:
docker build -t hodor-service .

### 3. Run the Docker Container:
docker run -d -p 8080:8080 hodor-service

### 4. Access the Hodor API:
Hodor API Endpoint: http://localhost:8080

#### Bran Service:
### 1. Clone the Repository:
git clone https://github.com/bhupenderyadav7424/bran.git <br>
cd bran
### 2. Install Python Dependencies:
pip install -r requirements.txt
### 3. Run the Django Server:
python manage.py runserver 0.0.0.0:8000
### 4. Access the Bran API:
Bran API Endpoint: http://localhost:8000


## Testing the APIs:
We can use tools like cURL, Postman, or any HTTP client to test the APIs. <br>
#### Examples:
For Hodor: curl http://localhost:8080 <br>
For Bran: curl http://localhost:8000 <br>


## Additional Notes:
1. Ensure Docker and Python are installed on our system to run the services locally. <br> 
2. Modify configurations as per your requirements in the respective service directories. <br>
3. Refer to the README files in each repository for more detailed instructions and configurations. <br>

By following these instructions, we can run the Hodor and Bran services locally and test their APIs. Feel free to explore the repositories for more information and customization options.
