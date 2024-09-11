# expo-static-issue
Created with npx create-expo-app@latest without further work 

steps to reproduce:

  1 - Build the website with npx expo export --platform web
  
  2 - In the browser, open the index.html produced inside the dist folder to verify the conent, it should be empty besides the navigation bar
  
  3 - Remove HelloWave from index.tsx and repeat the build with npx expo export --platform web
  
  4 - Open the index.html produced in the browser again, and now it should be prerendered with some content and text.
