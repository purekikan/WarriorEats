# Warriors-Eats
How to run on your computer (website)
1. Clone the repository
2. Run the following commands:
```bash
cd my-project        # Change directory to the project folder
npm install             # Install the dependencies
npx nx install my-app           # ensure the dependencies in my-app are installed
npx nx start my-app        # Start the frontend
```
open another terminal and run the following commands:
```bash
cd .\my-app\src\backend\    # Go to the backend API
touch .env # create a new file called .env
```
then open the .env file and add the following lines:
```bash
# .env example
PGHOST=localhost
PGDATABASE=warrioreats
PGUSER=warrioreats
PGPASSWORD=****** # your cloud database password
LOCALPW=****** # your local database password
PGPORT=5432
```
then run the following commands:
```bash
npm install   # Install the dependencies for backend API
npm index.js  # Start the backend API
```
3. Open your browser and go to http://localhost:19000 for frontend
4. Open your browser and go to http://localhost:3000 for backend API
5. Enjoy!

----------------------
Run on your mobile device:
1. Download the Expo Go app from the App Store or Google Play Store
2. type command in the terminal
```bash
cd .\my-project\my-app\   # Go to the app folder  
npx expo start
```
3. Make sure your mobile device is connected to the same network as your computer
4. Scan the QR code with your camera app
5. Enjoy!