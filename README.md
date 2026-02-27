# Instructions to set up this project!

Frontend - uses HTMl/CSS/JavaScript/ React Framework


1. Download git (version control software to download code)
- https://git-scm.com/install/
2. Download node.js (this allows you to run code on your laptop)
- https://nodejs.org/en
3. VS Code (Any code editor will do, this one is lightweight so it should be fine to use immediately)
- https://code.visualstudio.com/download

After installing this, open your terminal and you should be able to run the commands like this and see some version numbers appear. (If they don't consult ChatGPT to fix this you need to add the software to your PATH)
``` shell
git --version
npm --version
node --version
```

## Downloading the code
Open your terminal and go to your Desktop
``` shell
cd ~/Desktop
```
Download / clone the code repository
``` shell
git clone https://github.com/ElizaWong/FactSmith_G1
```
Go into the folder
``` shell
cd FactSmith_G1
```
Install dependencies
```
npm install
```
Run the project
```
npm run dev
```
Now you should be able to go to `localhost:5173` on your web browser and you should see the project running.


## Uploading code
Uploading your changes are a bit complicated - if two people edit the same piece of code there will be merge conflicts which are difficult to deal with! So it's best to communicate who is doing what.

Uploading code:
``` shell
git add .
git commit -m "Say what you changed here"
git push origin main
```

After someone has uploaded / pushed their code, everyone needs to download / pull those changes so their version is not out of date!
``` shell
git pull origin main
```

## Deployment
Deployment will be done later with github pages.
If you need help with anything else ask @ElizaWong

