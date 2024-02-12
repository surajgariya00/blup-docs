---
description: Create iOS release build on cloud. (Even if you are on Windows or Linux.)
---

# Configure ⚙️

To get started with iOS Cloud Build. First, we would have to configure the values. These values need to be set only once & later you can directly go to [run.md](run.md "mention") to Run iOS Cloud Build.

### To get started <a href="#code-signing" id="code-signing"></a>

Follow the image below to open the "App Store Details" dialog first.

<figure><img src="../../../.gitbook/assets/app store details.png" alt="Follow the image to open the &#x22;App Store Details&#x22; dialog first."><figcaption><p>Follow the image to open the "App Store Details" dialog first.</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/cloud build first tasks.png" alt="Let&#x27;s first fill the Issuer Id, Key Id &#x26; API Key."><figcaption><p>Let's first fill the Issuer Id, Key Id &#x26; API Key.</p></figcaption></figure>

## 1. Get the "Issuer Id, Key Id & API Key" <a href="#code-signing" id="code-signing"></a>

### Code signing <a href="#code-signing" id="code-signing"></a>

All applications have to be digitally signed before they are made available to the public to confirm their author and guarantee that the code has not been altered or corrupted since it was signed.

{% hint style="warning" %}
Signing iOS applications requires [Apple Developer Program](https://developer.apple.com/programs/enroll/) membership.
{% endhint %}

**Creating the App Store Connect API key**

It is recommended to create a dedicated App Store Connect API key for Blup in [App Store Connect](https://appstoreconnect.apple.com/access/api). To do so:

1. Log into App Store Connect and navigate to **Users and Access > Keys**.
2. Click on the + sign to generate a new API key.
3. Enter the name of the key and select an access level. We recommend choosing `App Manager` access rights, read more about Apple Developer Program role permissions [here](https://help.apple.com/app-store-connect/#/deve5f9a89d7).
4. Click **Generate**.
5. As soon as the key is generated, you can see it is added to the list of active keys. Click **Download API Key** to save the private key for later. Note that the key can only be downloaded once.

{% hint style="info" %}
Take note of the **Issuer ID** above the table of active keys as well as the **Key ID** of the generated key as these will be required when setting up the Apple Developer Portal integration in Blup.
{% endhint %}



**It would look something like this on your Apple Developer Account.**

<figure><img src="../../../.gitbook/assets/apple website.png" alt=""><figcaption><p>Issuer Id, Key Id &#x26; API Key</p></figcaption></figure>

## **2**. Get the "SSH Certificate Key" <a href="#code-signing" id="code-signing"></a>

<figure><img src="../../../.gitbook/assets/ssh certificate key.png" alt=""><figcaption></figcaption></figure>

### **Obtaining the Certificate private key**

To sign iOS apps, you can use the private key of an iOS Distribution certificate that has already been created in your Apple Developer Program account.

If you do not have a private key then you can create a new one.

#### Create a new key

You can create a new 2048-bit RSA key by running the command below in your terminal:

**For Mac:**

```
ssh-keygen -t rsa -b 2048 -m PEM -f ~/Desktop/ios_distribution_private_key -q -N ""
```

**For Windows:**

Open CMD, & type `ssh-keygen` . If this command doesn't work. Download OpenSSH from [here](https://slproweb.com/products/Win32OpenSSL.html).

<pre><code><strong>ssh-keygen -t rsa -b 2048 -m PEM -f ./MyKeyGen/ios_distribution_private_key -q -N ""
</strong></code></pre>



This new private key will be used to create a new iOS Distribution certificate in your Apple Developer Program account if there isn’t one that already matches this private key.



Paste this private key in Blup "**App Store Connect Dialog**".\
\
**Note:** Paste the keys _**with**_** `----BEGIN PRIVATE KEY----`** & **`-----END PRIVATE KEY-----`** as well.

<figure><img src="../../../.gitbook/assets/final ssh certificate key.png" alt=""><figcaption><p>Finally, it will look something like this.</p></figcaption></figure>



Next, let's run the cloud build! [run.md](run.md "mention")
