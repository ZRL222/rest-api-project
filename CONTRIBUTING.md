# CONTRIBUTING

## HOW to run the Dockerfile locally

'''
docker run -dp 5000:5000 -w /app -v "$(pwd):/app IMAGE_NAME sh -c "flask run --host 0.0.0.0"
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" flask-smorest-api 
'''