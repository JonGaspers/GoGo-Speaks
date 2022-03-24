# Web Microphone Websocket

This is an example of a ReactJS web application streaming microphone audio from the browser
to a NodeJS server and transmitting the DeepSpeech results back to the browser.

#### Download the pre-trained model (1.8GB):

```
wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm
wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.scorer
```
Set the pre-trained model files in `/deepspeech-0.9.3-models`

#### Install:
##### yarn
```
yarn install
```
##### npm
```
npm install
```
#### Run ReactJS Client:
##### yarn
```
yarn start
```
##### npm
```
npm start
```

#### Run NodeJS Server (in a separate terminal window):

```
node server.js
```
