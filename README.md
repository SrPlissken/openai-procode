<br/>
<p align="center">
  <h3 align="center">OpenAI - ProCode</h3>

  <p align="center">
    A Client-Server App using OpenAI API
    <br/>
    <br/>
    <a href="https://openai-procode.vercel.app/">View Demo</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/SrPlissken/openai-procode/total) ![Contributors](https://img.shields.io/github/contributors/SrPlissken/openai-procode?color=dark-green) ![Issues](https://img.shields.io/github/issues/SrPlissken/openai-procode) 

## About The Project

<img src="/images/screenshot.png?raw=true" width="50%" height="50%">


## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Installation

1. Get a free API Key at [https://beta.openai.com/](https://beta.openai.com/)

2. Clone the repo

```sh
git clone https://github.com/SrPlissken/openai-procode.git
```

3. Download Nodejs from [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

4. Install NPM packages

```sh
npm install
```

5. Create .env file inside server folder and enter your API Key

```JS
OPENAI_API_KEY = 'ENTER YOUR API';
```

## Usage

1. Open Terminal and navigate to server folder and run following command:

```sh
cd .\server\
npm run server
```

2. Copy hyperlink server output and find serverEndPoint inside client folder in script.js at begining of file:

```JS
const serverEndPoint = 'http://localhost:5001';
```

3. Navigate to client folder and run with following command:

```sh
cd .\client\
npm run dev
```

## Authors

* **SrPlissken** - *Dev* - [SrPlissken](https://github.com/SrPlissken) - *OpenAI - ProCode*

## Acknowledgements

* [ JavaScript Mastery](https://www.youtube.com/watch?v=2FeymQoKvrk&t=3176s)