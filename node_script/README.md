# Instructions

1. Get the data (in the Json format): http://data.assemblee-nationale.fr/travaux-parlementaires/votes
2. Unzip the archive file in the /sources folder of this directory
3. Make sure you have downloaded and install Node: https://nodejs.org/en/download/ (it should also install npm)
4. Open your terminal
5. Install the dependencies of the project by executing the following command

```js
$ sudo npm i
```

6. Still in your console, execute the following command. This will launch the execution of the cleaning script.

```js
$ node index.js
```

7. Hop! You should now have a clean `tree.json` file in the /tree folder. This Json will be used by the dataviz to display the votes.
