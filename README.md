<img align="center" src="https://raw.githubusercontent.com/Kommunicate-io/Kommunicate-Android-Chat-SDK/master/img/Header.png" width="900" />

## [Kommunicate](https://www.kommunicate.io/?utm_source=github&utm_medium=readme&utm_campaign=android) Android Chat SDK for Customer Support

An Open Source Android Live Chat SDK for Customer Support


## Get Started

To get started with Kommunicate Android SDK, head over to the Kommunicate website and [Signup](https://dashboard.kommunicate.io/signup?utm_source=github&utm_medium=readme&utm_campaign=android) to get your Application ID.

This is a sample that implements the Kommunicate android chat SDK. To use this sample you need to provide your application ID in app level build.gradle file's defaultConfig [Refer here](https://github.com/Kommunicate-io/Kommunicate-Android-Chat-SDK/blob/f78948edd81124847d1b6ee2179eadd968ec57b1/app/build.gradle#L13). Replace <Your-APP_ID> with the application ID obtained from Kommunicate dashboard.

## Dialogflow chatbot integration in your Android app

Dialogflow is a Google-owned NLP platform to facilitate human-computer interactions such as chatbots, voice bots, etc. 

Kommunicate's Dialogflow integration provides a more versatile, customizable and better chatting experience. Kommunicate Android Live Chat SDK supports all of Dialogflow's features such as Google Assistant, Rich Messaging, etc. On top of that, it is equipped with advanced features such as bot-human handoff, conversation managing dashboard, reporting, and others. 

You can connect your Dialogflow chatbot with Kommunicate in the following 4 simple steps. [Here](https://www.kommunicate.io/blog/build-chatbot-with-dialogflow-android-sdk/) is a step by step blog to add Kommunicate SDK in your Android app. 

### Step 1: Get your API credentials from Dialogflow
- Login to Dialogflow console and select your agent from the dropdown in the left panel.
- Click on the settings button. It will open a setting page for the agent.
- Inside the general tab search for GOOGLE PROJECTS and click on your service account.
- After getting redirected to your SERVICE ACCOUNT, create a key in JSON format for your project from the actions section and it will get automatically downloaded.

### Step 2: Create a free Kommunicate account
Create a free account on [Kommunicate](https://dashboard.kommunicate.io/signup) and navigate to the [Bots section](https://dashboard.kommunicate.io/bots/bot-integrations).

### Step 3: Integrate your Dialogflow chatbot with Kommunicate
- In the Bot integrations section, choose Dialogflow. A popup window will open.
- Upload your Key file here and proceed.
- Give a name and image to your chatbot. It will be visible to the users chatting with your chatbot.
- Enable/Disable chatbot to human handoff. If enabled, it will automatically assign conversations to humans in case the chatbot is not able to answer.

### Step 4: Install the Kommunicate Android SDK to your app
You can add the Kommunicate SDK in your Android app easily. More information on how to integrate with your Andriod app [here](https://docs.kommunicate.io/docs/android-installation.html). 

> Note: Here's a [sample chatbot](https://docs.kommunicate.io/docs/bot-samples) for you to get started with Dialogflow. 


