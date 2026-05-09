# Base image
FROM python:3.14-slim
# Directory
WORKDIR /app
# Copy code 
COPY . .
# Install
RUN pip install -r requirements.txt
# Expose port
EXPOSE 3001
# Run app
CMD ["python","app.py"]
