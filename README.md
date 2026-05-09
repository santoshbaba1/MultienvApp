# MultiEnv Ticket Management System

A full-stack application using Flask for both frontend and backend services, demonstrating environment-specific ticket management.

## Project Structure

```
multienv/
├── docker-compose.yml
├── backend/
│   ├── dev/
│   │   ├── app.py
│   │   ├── requirements.txt
│   │   ├── Dockerfile
│   │   └── .env
│   └── prod/
│       ├── app.py
│       ├── requirements.txt
│       ├── Dockerfile
│       └── .env
└── frontend/
    ├── app.py
    ├── requirements.txt
    ├── Dockerfile
    └── .env
```

## Environment Configuration

### Backend Development Environment (.env)
```
PORT=3001
MONGO_URI=your_dev_mongodb_uri
```

### Backend Production Environment (.env)
```
PORT=3002
MONGO_URI=your_prod_mongodb_uri
```



### Requirements
```
flask==2.0.1
flask-cors==3.0.10
python-dotenv==0.19.0
pymongo==3.12.0
requests==2.26.0
```



### Using Docker Compose
```bash
docker-compose up
```

## Accessing the Application

- Frontend: http://localhost:3000/
- Development Environment: http://localhost:3001/dev
- Production Environment: http://localhost:3002/prod
<img width="1365" height="214" alt="git clone 1" src="https://github.com/user-attachments/assets/5f790229-924c-4742-a47d-879e0ec50234" />
<img width="1918" height="402" alt="build 1" src="https://github.com/user-attachments/assets/757783ff-98ae-4611-a83d-20e7a69b9f8d" />
<img width="1905" height="1007" alt="build 2" src="https://github.com/user-attachments/assets/c66a14ff-a06c-46eb-acb6-226934b8dbda" />
<img width="1912" height="348" alt="fe" src="https://github.com/user-attachments/assets/f60ddbb3-5935-4da6-9041-4fdb0fe208c5" />
<img width="1911" height="467" alt="be dev-1" src="https://github.com/user-attachments/assets/1c95b59c-6460-43c8-bbf9-414675c07ace" />
<img width="1857" height="537" alt="be-pro-1" src="https://github.com/user-attachments/assets/52655aa3-6ca4-4ed4-90cb-3ec78bbe2fb1" />
<img width="1918" height="1027" alt="prod ui-1" src="https://github.com/user-attachments/assets/25eeee3d-348b-4294-8470-9145fa9226ac" />
<img width="1917" height="1028" alt="dev ui1" src="https://github.com/user-attachments/assets/58df04a8-81fa-408a-86ef-d0f2e1994d0c" />
<img width="1916" height="986" alt="dev db-1" src="https://github.com/user-attachments/assets/1249a572-f18e-4fa5-9f5a-0b8c6c6e1056" />
<img width="1918" height="1017" alt="prod" src="https://github.com/user-attachments/assets/a32b07f8-9eb6-4fd3-8f91-11820f72e698" />
<img width="1918" height="1027" alt="prod ui-1" src="https://github.com/user-attachments/assets/a4a214c5-3d29-4818-a513-f1c845a65af1" />








## Security Considerations


- Never commit `.env` files to version control
- Use different MongoDB databases for dev and prod
- Implement proper authentication
- Use secure headers

## 👨‍💻 Author

**Santosh Kumar Sharma (12394)**
DevOps & Cloud Enthusiast
