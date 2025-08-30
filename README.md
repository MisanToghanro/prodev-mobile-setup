# prodev-mobile-setup

# ProDev Mobile App 0x00

## Scaffolding Steps
1. Initialized the project using Expo:
   npx create-expo-app@latest prodev-mobile-app-0x00

2. Navigated into the project folder:
    cd prodev-mobile-app-0x00

3. Installed dependencies:    
    npm install

4. Started the application to confirm it runs:
    npx expo start

## Resetting the Project

To reset the project, I ran:

npm run reset-project        

### Observations

1. The command deleted the node_modules folder, lock files (package-lock.json), and cache directories (like .expo).

2. After cleanup, it reinstalled all dependencies from package.json.

3. The project was restored to a clean state, as if freshly scaffolded.

4. Running npx expo start after the reset confirmed that the app still builds and runs successfully.