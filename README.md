# Hackathon Osnabrück

## Table of Contents
  * [1. Register a Bluemix Account](#bluemixlogin)
  * [2. Create an Application](#createapp)
  * [3. IBM Watson Services](#services)
  * [4. Hands on Programming!](#programming)
    * [4.1 Python](#python)
      * [4.1.1 AlchemyLanguage](#alchemylanguage)
      * [4.1.2 AlchemyVision](#alchemyvision)
      * [4.1.3 AlchemyData News](#alchemydata-news)
      * [4.1.4 Authorization](#authorization)
      * [4.1.5 Concept Insights](#concept-insights)
      * [4.1.6 Conversation](#conversation)
      * [4.1.7 Dialog](#dialog)
      * [4.1.8 Document Conversion](#document-conversion)
      * [4.1.9 Language Translator](#language-translator)
      * [4.1.10 Natural Language Classifier](#natural-language-classifier)
      * [4.1.11 Personality Insights](#personality-insights)
      * [4.1.12 Relationship Extraction](#relationship-extraction)
      * [4.1.13 Retrieve and Rank](#retrieve-and-rank)
      * [4.1.14 Speech to Text](#speech-to-text)
      * [4.1.15 Text to Speech](#text-to-speech)
      * [4.1.16 Tone Analyzer](#tone-analyzer)
      * [4.1.17 Tradeoff Analytics](#tradeoff-analytics)
      * [4.1.18 Visual Insights](#visual-insights)
      * [4.1.19 Visual Recognition](#visual-recognition)
    * [4.2 NodeJS](#nodejs)
      * [4.2.1 AlchemyLanguage](#alchemylanguage2)
      * [4.2.2 AlchemyVision](#alchemyvision2)
      * [4.2.3 AlchemyData News](#alchemydata-news2)
      * [4.2.4 Authorization](#authorization2)
      * [4.2.5 Concept Insights](#concept-insights2)
      * [4.2.6 Conversation](#conversation2)
      * [4.2.7 Dialog](#dialog2)
      * [4.2.8 Document Conversion](#document-conversion2)
      * [4.2.9 Language Translator](#language-translator2)
      * [4.2.10 Natural Language Classifier](#natural-language-classifier2)
      * [4.2.11 Personality Insights](#personality-insights2)
      * [4.2.12 Relationship Extraction](#relationship-extraction2)
      * [4.2.13 Retrieve and Rank](#retrieve-and-rank2)
      * [4.2.14 Speech to Text](#speech-to-text2)
      * [4.2.15 Text to Speech](#text-to-speech2)
      * [4.2.16 Tone Analyzer](#tone-analyzer2)
      * [4.2.17 Tradeoff Analytics](#tradeoff-analytics2)
      * [4.2.18 Visual Insights](#visual-insights2)
      * [4.2.19 Visual Recognition](#visual-recognition2)


<a name="bluemixlogin" />
## 1. Register a Bluemix Account
Go to http://bluemix.net and click on "[Sign up](https://console.ng.bluemix.net/registration/)". Fill in the form and follow the instructions. Your account will be free for the next 30 days. After that period no charges will apply. Your account will simply be suspended unless you enter your billing information.

Finally you can [log in](https://idaas.iam.ibm.com/) your newly created account.


<a name="createapp" />
## 2. Create an Application
The Bluemix environment gives you the opportunity to create web or mobile applications. Staging and configuring such apps may require some additional knowledge, e.g. how web servers work and perhaps understanding of web technologies such as HTML.

### 2.1 Locally
We recommend that you work **locally** on your computer.

In that case - you can **skip this section**.

### 2.2 Online
If you anyway want to stage your application online:
  - Click **Create Application**
  - Pick one of the containers/boilerplates.
   - For Python programmers we recommend using **Boilerplates** > **Python Flask**
   - For NodeJS fans we recommend **Cloud Foundry Apps** > **SDK for NodeJS**
  - Enter `App Name`
  - Click **Create**
  - Follow the instructions

**Important:** the **Bluemix** and **CF** command line interfaces are already installed on our computers


<a name="services" />
## 3. IBM Watson Services

### 3.1 Creating a Service
...

### 3.2 Getting the Service Credentials
You will need the `username` and `password` (`api_key` for AlchemyAPI) credentials for each service. Service credentials are different from your Bluemix account username and password.

To get your service credentials, follow these steps:
 1. Log in to Bluemix at https://bluemix.net.

 1. Create an instance of the service:
     1. In the Bluemix **Catalog**, select the service you want to use.
     1. Under **Add Service**, type a unique name for the service instance in the Service name field.
     
     For example, type `my-service-name`. Leave the default values for the other options.
     1. Click **Create**.

 1. Copy your credentials:
     1. On the left side of the page, click **Service Credentials** to view your service credentials.
     1. Copy `username` and `password`(`api_key` for AlchemyAPI).

<a name="programming" />
## 4. Hands on Programming!

<a name="python" />
### 4.1 Python
...

<a name="nodejs" />
### 4.2 NodeJS
...
