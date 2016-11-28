# Hackathon Osnabrück

## Table of Contents
  * [1. Register a Bluemix Account](#bluemixlogin)
  * [2. Create an Application](#createapp)
  * [3. IBM Watson Services](#services)
  * [4. Hands on Programming!](#programming)
    * [4.1. Python](#python)
    * [4.2. NodeJS](#nodejs)
    * [4.3. Java](#java)


<a name="bluemixlogin" />
## 1. Register a Bluemix Account
Go to http://bluemix.net and click "[Sign up](https://console.ng.bluemix.net/registration/)". Fill in the form and follow the instructions. Your account will be free for the next 30 days. After that period no charges will apply. Your account will simply be suspended unless you enter your billing information.

Finally you can [log in](https://idaas.iam.ibm.com/) your newly created account.


<a name="createapp" />
## 2. Create an Application
The Bluemix environment gives you the opportunity to create web or mobile applications. Staging and configuring such apps may require some additional knowledge, e.g. how web servers work and perhaps understanding of web technologies such as HTML.

### 2.1. Locally
We recommend that you work **locally** on your computer.

In that case - you can **skip this section**.

### 2.2. Online
If you anyway want to stage your application online:
  - Click **Create Application**
  - Pick one of the containers/boilerplates.
   - For Python programmers we recommend using **Boilerplates** >> **Python Flask**
   - For NodeJS fans we recommend **Cloud Foundry Apps** >> **SDK for NodeJS**
  - Enter `App Name`
  - Click **Create**
  - Follow the instructions

**Important:** the **Bluemix** and **CF** command line interfaces are already installed on the computers in the pool.


<a name="services" />
## 3. IBM Watson Services

### 3.1. Creating a Service
- Go to **Catalog** >> **Services** >> **Watson**
- Click on the desired service
- Enter a unique service name or leave the default value
- If you decided to stage an online app: on the left side under "Connect to" you can associate it to your application (optional)
- Click **Create**

### 3.2. Getting the Service Credentials
You will need the `username` and `password` (`api_key` for AlchemyAPI) credentials for each service. Service credentials are different from your Bluemix account username and password.

- Click on the service you created
- On the left side of the page, click **Service Credentials** to view your service credentials.
- Copy `username` and `password`(`api_key` for AlchemyAPI).

<a name="programming" />
## 4. Hands on Programming!
In theory - any modern programming language can be used with the Watson Services. However using the native RESTful API might turn out to be quite difficult to handle. The [Watson Developer Cloud](https://github.com/watson-developer-cloud) provides us with some useful packages when working with popular programming languages like Python, NodeJS, Java, etc.

<a name="python" />
### 4.1. Python

#### 4.1.1. Virtual Environment
You might not have privilleges to install python packages on the computers in the pool. However you can create a virtual environment and install any package you need there. To do that - follow the instructions:
- Create a folder for your project
- Open a Terminal in that folder
- Type `virtualenv venv` (you can substitute `venv` with your prefered name)
- To activate the virtual environment type: `source venv/bin/activate`
- Now you are operating in the virtual environment

#### 4.1.2. Using the Watson Developer Cloud package
Simply open a terminal and type:
```sh
$ pip install watson_developer_cloud
```

Create a new file, e.g. `my_app.py` and include the desired service like so:
```python
from watson_developer_cloud import RetrieveAndRankV1

...
...
...
```

Now you can use the `Retrieve and Rank` service. For more detailed information on how to use the services - check out the **examples** folder at: https://github.com/watson-developer-cloud/python-sdk

<a name="nodejs" />
### 4.2. NodeJS
Unfortunately NodeJS is not installed on the computers in the pool. However if you prefer Javascript as your programming language - you can still do this on your personal notebook. To install the **Watson Developer Cloud** package via npm, simply open a terminal and type:
```sh
$ npm install watson-developer-cloud
```
Examples and more detailed information on how to use the services you can find at: https://github.com/watson-developer-cloud/node-sdk

<a name="java" />
### 4.3. Java
For examples and more detailed information, please visit: https://github.com/watson-developer-cloud/java-sdk
