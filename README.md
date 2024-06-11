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
2. **Build Docker Image**
    ```bash
    docker build -t characternavigator .
    ```
   
3. **Run Docker Container**
   ```bash
   docker run -e "SigningSecret=32-character-long-secure-password" -p 5025:8080 --name containername characternavigator
   ```

4. **Enter Responsive Mode**

   The app is currently only supported in responsive mode.

   To enter responsive mode, open the developer tools (F12 or right click -> Inspect) and ensure that "Toggle device emulation" is enabled in the top left corner of the developer tools.
   
6. **Log In**

   Log into the application by entering the following credentials:
   ```
   Username: admin
   Password: admin123
   ```

## Project Repositories
The project is contained within three repositories:

**Front-end**: https://github.com/character-navigator/frontend <br/>
**Back-end**: https://github.com/character-navigator/backend <br/>
**ML-service**: https://github.com/character-navigator/ml-service
