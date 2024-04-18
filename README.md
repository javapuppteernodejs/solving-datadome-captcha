# How to Solve DataDome: Complete Guide 2024
![](https://assets.capsolver.com/prod/images/post/2024-04-18/31eb8335-9c2d-43dc-92dc-93bdce028e69.png)

DataDome is a powerful anti-data scraping protection system widely employed by some companies, to protect their websites from data scraping. It employs advanced technology that poses a significant challenge to solving the system.

Despite the complexity of DataDome's measures, there are tools that can help break through its defences and enable reliable data scraping. In this guide, we'll explore ways to solve DataDome so you can choose the method that best suits your needs.

**Table of Contents:**
- Understanding DataDome and Its Purpose
- What does DataDome do to detect robots?
    - Server-side Measures
    - Client-side Measures
- How to Solve DataDome
    - Automated Browsers
    - High-Quality Proxies
    - CAPTCHA Solving Services
- Solving DataDome Captcha
## Understanding DataDome and Its Purpose
DataDome's implementation of CAPTCHA is an integral part of their defense mechanism against bots. CAPTCHA, an acronym for "Completely Automated Public Turing test to tell Computers and Humans Apart," is a test designed to distinguish between human users and automated bots.

When DataDome's system identifies suspicious activity that indicates the presence of a bot, it may prompt a CAPTCHA challenge. The purpose of this challenge is to ensure that the user attempting to access the website or application is genuinely human. By successfully completing the CAPTCHA, the user verifies their human identity and gains access to the desired content or functionality.

![](https://assets.capsolver.com/prod/images/post/2023-05-12/8e31f4fb-08b8-453e-a0da-38a68b16e905.png)

## What does DataDome do to detect robots?

DataDome employs a combination of server-side and client-side techniques to detect bots, utilizing various factors such as user behavior, network and browser fingerprints, geolocation tracking, and more. These measures are regularly updated and maintained to adapt to the evolving landscape of bots.

Let's explore the key detection techniques used by DataDome, categorized into server-side and client-side measures, which are fundamental to understanding how solve DataDome's detection.

### Server-side Measures:
DataDome's server-side measures focus on analyzing the connection to the server, browsing sessions, and related metadata. By leveraging protocols like HTTP, TCP, and TLS, these measures generate user fingerprints and identify inconsistencies or suspicious behavior.
  
#### **TCP/IP Fingerprinting:**

Networked devices reveal characteristics from the initial TCP/IP request, including parameters such as Time-To-Live (TTL) and support for IP fragmentation.

#### **HTTP/2 Fingerprinting:**

DataDome utilizes HTTP/2, a binary protocol that enhances website and application performance through features like header field compression and concurrent requests on the same TCP connection.

#### **TLS Fingerprinting:**

TLS fingerprinting helps web servers identify the client's identity (e.g., browsers, CLI tools, scripts) using the parameters from the initial connection packet before any application data exchange occurs.

#### **Server-side Behavioral Analysis:**

DataDome analyzes browsing sessions, logs, requests, IP addresses, and interactions with honeypots to detect anomalies and outliers. Unusual request frequencies may trigger rate-limiting, while a change in the country of origin during a browsing session could indicate proxy usage.

### Client-side Signals:
Client-side signals are collected from end-user devices and can be obtained through JavaScript (JS) or mobile application SDKs. These signals provide valuable insights for bot detection. Here are some techniques used:

#### **Operating System and Hardware Data:**  

Operating System fingerprinting, including details on CPU, GPU, device models, vendors, and manufacturers, helps identify vulnerable OS versions. Hardware data, which is even more resistant to change, provides additional information.

#### **Browser fingerprinting**  

Browser fingerprinting is a method used to identify web browsers by gathering various information about them, including browser type, version, screen resolution, and IP address. This aggregated data forms a unique "fingerprint" that can be used to track browsers across different websites and browsing sessions.

Browser fingerprinting techniques encompass several methods, such as:

**Canvas Fingerprinting**: This technique utilizes the HTML5 canvas element to extract information about a browser's rendering capabilities, which can be used to create a unique fingerprint.

**Audio Fingerprinting**: By analyzing audio output capabilities and characteristics, audio fingerprinting can be used to differentiate browsers.


## How to Solve DataDome
To overcome DataDome's protective measures, we need to employ a combination of tactics learned from previous experiences. DataDome employs sophisticated bot detection techniques both on the server and client sides, such as TLS fingerprinting and browser fingerprinting. To solve DataDome's defenses and extract the desired data, we must operate stealthily within its radar.

Here are several effective strategies:

### Automated Browsers

Tools like Selenium and Puppeteer are invaluable for automation tasks. However, they typically leave conspicuous traces of their automated nature. To tackle DataDome protection, utilize masking packages like puppeteer-extra-plugin-stealth for Puppeteer, selenium-stealth for Selenium, or playwright-stealth for Playwright. While the specifics may vary, the underlying principle remains consistent. These extensions address browser fingerprint inconsistencies, manipulate browser JavaScript variables, and eliminate telltale signs of automation.

### High-Quality Proxies
   
Proxies play a crucial role in web scraping by shielding and diversifying your IP address, facilitating data extraction. Datacenter and residential proxies are particularly effective against DataDome. Consider the merits of static and rotating proxies: static proxies offer a fixed IP address, but excessive requests may trigger detection. Rotating proxies, on the other hand, constantly change IP addresses, providing a more discreet approach to scraping.

### CAPTCHA Solving Services

DataDome often employs CAPTCHA challenges as an additional layer of defense. CAPTCHA-solving services come in two primary forms, sometimes even combining elements of both:

   a. **Automated CAPTCHA Solvers:** These solutions leverage machine learning techniques such as optical character recognition (OCR) and object detection to swiftly solve challenges. They offer speed and efficiency in solving CAPTCHAs.
   
   b. **Human Workers:** Alternatively, manual CAPTCHA solving by a team of human workers is available, albeit slower and more costly. Although the accuracy of this method can be guaranteed, but with the accuracy of machine learning is now gradually improved and there is no gap between human. Moreover, this method lacks the immediacy required for certain tasks.

## Bonus Code
 A bonus code for top captcha solutions; [CapSolver](https://www.capsolver.com/): **WEBS**. After redeeming it, you will get an extra 5% bonus after each recharge, Unlimited

![](https://assets.capsolver.com/prod/images/post/2024-03-29/fbc29472-886c-45b2-9eb2-2b307f6d9700.png)

   
   
## Solving DataDome Captcha

For expedient and cost-effective CAPTCHA resolution, automated solutions like [Capsolver](https://www.capsolver.com/) are recommended. So next, we will talk about how to solve DataDome through an automated captcha solution.


Before we start solving DataDome, there are some requeriments and points that we need to be aware that they are needed to know



**🔒 Requeriments:**
- Capsolver Key
- Proxy

**🪄 Points to be aware that if you don't follow, solution will be invalid:**
- **The query parameters** of the captcha url are obtained dynamic. This mean that you can't send a static captcha url over and over.
  The query parameters are the bold words: https://geo.captcha-delivery.com/captcha/?**initialCid**=yourInitialCid&**cid**=yourCid&**t**=fe&**referer**=https%3A%2F%2Fantoinevastel.com%2Fbots%2Fdatadome&**s**=YourSParam&**e**=youreParam **these are obtained in the first GET where you get the captcha**
- **The query param** t, need to have the value t=fe, if have t=bv, this mean the captchaUrl is banned and you can't submit us that.
- **Match** the TLS of the chrome version, header and header order.
- **Match** the proxy used for solve the captcha for interact with the page
- **User Agent** must be obtained from the documentation
  ![](https://assets.capsolver.com/prod/images/post/2023-12-06/67f6c5ff-e831-4924-bc67-2cf8c86a2d78.png)
 **Check the documentation to obtain the latest**

Make sure that you understand all the points to make sure capsolver can solve the captcha correctly.

To solve datadome captcha you also need to understand our documentation: [documentation](https://docs.capsolver.com/guide/antibots/datadome.html).

If any parameter is missing, you will likely encounter issues with the token not being accepted by the website. 

The first method that you need to use from the documentation is `createTask`, this method need the parameters of the picture.
![](https://assets.capsolver.com/prod/images/post/2023-05-11/3f9e93fd-ecdb-45d8-8c81-aff582c5b6fc.png)
**Some parameters are required and some are optional. Depends where you want to solve DataDome Captcha**
For this example, we will only use the required parameters. The task types for datadome are:

- ``DatadomeSliderTask``: This task type requires your own proxies.

For this example, we will use **DatadomeSliderTask** as the site uses datadome captcha.

After read this basic guide to understand how you should do it, you are ready for solve datadome. So let's start!

### Step 1: Submit the information to Capsolver
Use the method `createTask` for submit the information:


```JSON
POST https://api.capsolver.com/createTask

{
"clientKey": "Your_API_KEY",
"task": {
"type": "DatadomeSliderTask",
"websiteURL": "https://antoinevastel.com/bots/datadome",
"captchaUrl": "https://geo.captcha-delivery.com/captcha/?initialCid=yourInitialCid&cid=yourCid&t=fe&referer=https%3A%2F%2Fantoinevastel.com%2Fbots%2Fdatadome&s=YourSParam&e=youreParam",
"proxy": "yourproxy",
"userAgent": "check documentation for get user agent that you must use"
  }
}
```
### Step 2: Get the results

To verify the results, you'll need to continuously poll the `getTaskResult` API endpoint until the captcha is resolved. 

Here's an example request:

```json
POST https://api.capsolver.com/getTaskResult
Host: api.capsolver.com
Content-Type: application/json

{
    "clientKey":"YOUR_API_KEY",
    "taskId": "TASKID_OF_CREATETASK" //ID created by the createTask method
}

```
Once the captcha is successfully resolved, you'll receive a response similar to the one depicted in the following image:
![](https://assets.capsolver.com/prod/images/post/2023-05-11/af01f1dd-9a30-46b6-a536-b43129df8d1a.png)

The captcha token received can be verified by submitting the cookie `datadome` with the value of the response to the relevant site. 
> ⚠️ **If the token is rejected, it may indicate that some information is missing or incorrect.
>  Make sure your TLS is correct (TLS matching the user agent used, good headers, headers order) and the same proxy used for solve the captcha is being used.**

## Wrapping Up
In conclusion, solving DataDome's robust anti-data scraping protection requires a combination of tactics such as automated browsers, high-quality proxies, and CAPTCHA-solving services. By carefully navigating the server-side and client-side measures implemented by DataDome, it is possible to solve its defenses and extract the desired data. Also at the end we tutored how to solve DataDome by automating the captcha solution, Capsolver 

