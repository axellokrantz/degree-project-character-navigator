# Character Navigator
## Degree Project

Character Navigator is an application developed by KTH students Daniel Dahlberg and Axel Månson Lokrantz as part of their bachelor thesis project, and represents a collaborative endeavor with <a href="https://www.bookbeat.com">BookBeat</a>. Here you can read the thesis or try the prototype yourself.

## How to run
Run the project with Docker:

1. **Clone the back-end repository**
   ```bash
   git clone https://github.com/character-navigator/backend
   cd backend
   ```

3. **Build Docker Image**
    ```bash
    docker build -t characternavigator .
    ```

4. **Run Docker Container**
   ```bash
   docker run -e "SigningSecret=32-character-long-secure-password" -p 8080:8080 --name containername characternavigator
   ```

## Project Repositories
The project is contained within three repositories:

**Front-end**: https://github.com/character-navigator/frontend <br/>
**Back-end**: https://github.com/character-navigator/backend <br/>
**ML-service**: https://github.com/character-navigator/ml-service
