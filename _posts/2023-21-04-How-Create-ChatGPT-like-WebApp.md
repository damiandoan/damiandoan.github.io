---
title: "How to create chatgpt like website in 5 minutes"
date: 2023-04-21 18:08:00 +0700
comments: true
categories: [website, reactJS]
tags: [reactJS, openAI, chatGPT, github, deployment]     # TAG names should always be lowercase
---

<!-- ---
title: How to create chatgpt like website in 5 minutes
date: 2022-04-21 18:08:00 -700
categories: [website, reactJS]
tags: [ reactjs, google cloud, chatgpt, ai]
--- -->

ChatGPT has been storming the tech world since November 2022, offering numerous opportunities to enhance productivity and even create businesses. OpenAI is now opening up its API for ChatGPT 3.5 with a free discount of $18, providing an excellent opportunity for us to utilize it and create innovative products.

Today, I will guide you through creating a ChatGPT-like website in just five minutes, including deployment.

## 1. Create Chatgpt account to obtain API key

Sign up a chatgpt account if you don't have one

👉 <a href="https://chat.openai.com/chat">https://chat.openai.com/chat<a>

Obtain API key by go to API keys page

👉 <a href="https://platform.openai.com/account/api-keys">https://platform.openai.com/account/api-keys</a>

![alt openai get api keys](/assets/img/examples/get_openai_api_keys.png)

Create new secret key then copy to save somewhere safe, we will use it later


> Remember to check the expiration date or remaining usage of your account, as the free discount is only available for four months after the account is created.
{: .prompt-tip }
## 2. Get the reactJS web app version of chatGPT

Clone or fork this <a href="https://github.com/katzenundhundle/react-chatGPT-clone">repository</a>: 
```shell
git clone https://github.com/katzenundhundle/react-chatGPT-clone
```

### Install client dependencies
```shell
cd client
npm install
```
### Install server dependencies
```shell
cd server
npm install
```

### Environment Variable Setup
Go to server folder and create .env file in root of server folder and create a variable REACT_APP_OPENAI_API_KEY = [ [Your Open AI key here](#1-create-chatgpt-account-to-obtain-api-key) ] insise .env file as

```
REACT_APP_OPENAI_API_KEY = [Your Open AI key here]
```

### Start the client
```
cd client
npm start
```

### Start the server
```
cd server
node index.js
```
Check if your client application run on port 3000 with the development environment configuration, so in your browser just go to http://localhost:3000

Check if your server application run on port 4000

<!-- ### result -->



