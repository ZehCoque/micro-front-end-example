# micro-front-end-example
Exemple of a MicroFrontEnd architecture.

# How to clone

Perform a ```git clone``` normally. After the download, go to the main directory and perform two commands:

```
git submodule init
git submodule update
```

# How to run

After you clone this repository, go to each folder and run the command:

```
npm install
```

After everything is installed, open 3 terminals, one for each folder.

For the ```root-config``` project, run the command:

```
npm start
```

For the ```angular-app``` project, run the command:

```
npm run serve:single-spa:angular-app
```

For the ```react-app``` project, run the command:

```
npm start
```

After everything is running, go to ```http://localhost:9000/``` in your browser.
