#Use Python Image
FROM python:3.7
# Set work directory
WORKDIR /app

COPY . .
# Install apt dependencies
 RUN pip install Flask Flask-SQLAlchemy PyMySQL
# run pip dependencies
 
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["python", "app.py"]
