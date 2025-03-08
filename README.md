#  Basic Docker project

## **Project overview**
 * Basics of Docker by containerizing a simple web application.
 
## **Prerequisites**

* Python  3.13.1 (Flask 3.1.0) 
* Docker version 27.5.1

## **Project Structure**

```bash
Containerized-Web-Application-Beginer/
├── app.py #   Flask  app
├── Dockerfile # Dockerfile  to containerise the flask app
├── requirements.txt # Dependencies 
```
## **TODO**

### **Clone the repo**
```bash
git clone  https://github.com/sekedoua/Containerized-Web-Application-Beginer.git
```
### **Build & Run the Docker Image**
```bash
cd Containerized-Web-Application-Beginer

docker build -t flask-app ..
```
### **Run the container:**
```bash
docker run -p 5000:5000 flask-app
```

### **Verify the Application:**
```bash
Open http://localhost:5000 in your browser.
---