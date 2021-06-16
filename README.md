# Important Instructions
1. Please use hshar/flaskapp as the base image in the Dockerfile
2. The table name to be created in Azure SQL is "Person5", if you want to use another name, you can change it in the hello.py file
3. Please enter all the values in the config.py file
4. If you want to have a look at the dataset it's OnlineRetail.csv
5. If you want to understand the ML code, you can check kmeans.py file
6. To run the flask code, please use the following commands:
git clone <github-link>
cd ./azure-devops-datascience
pip3 install -r requirements.txt
python3 hello.py

7. Remember without entering the correct values in config.py file, the code will not function properly and will give errors
