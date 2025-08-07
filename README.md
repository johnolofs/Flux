# **🌐 Timpi Node Deployment Guide**

This guide covers two separate methods for deploying Timpi Nodes:

* **FluxCloud** – for simplified and affordable Collector, and Geocore Node deployment via the Flux Marketplace.

* **FluxEdge** – for advanced, customizable infrastructure with Synaptron and Collector nodes.

---

## **🚀 Part 1: Deploying a Timpi Collector or Geocore Node via FluxCloud**

### **Step 1: Install the TimpiCollector App**

1. **Visit** [home.runonflux.com](http://home.runonflux.com)

2. **Sign in or create an account** using one of the following:

   * Apple ID

   * Google

   * Email

   * Zelcore / SSP / MetaMask / other Web3 wallets

<img width="1919" height="989" alt="image7" src="https://github.com/user-attachments/assets/27a010ce-74a9-473b-9080-5125ed2991d5" />


3. From the left-hand menu, go to **Applications → Marketplace**.**Search** for **TimpiCollector** or **TimpiGeoCore** and click on the desired app.

<img width="1918" height="984" alt="image3" src="https://github.com/user-attachments/assets/025047db-a6ac-4d7b-9830-2baeae5b2480" />


4. **App Configuration**  
   * TimpiCollector  
     1. Enter your email in the Contact field (optional, for expiration reminders).  
     2. Select your subscription period.  
     3. Agree to the Terms of Service by toggling the switch.  
     4. Click Start Launching Marketplace Application.

<img width="1919" height="987" alt="image19" src="https://github.com/user-attachments/assets/f8a48e8b-905e-4b1a-a964-8b188eaedcfd" />


* TimpiGeoCore  
  1. Enter your email in the Contact field (optional, for expiration reminders).  
     2. Select your subscription period.  
     3. Enter your registered GUID.  
     4. Agree to the Terms of Service.  
     5. Click Start Launching Marketplace Application.

<img width="1918" height="989" alt="image16" src="https://github.com/user-attachments/assets/362ee1ba-43ca-4860-a67b-8bbf9bdcb207" />

5. On the next screen, review the registration message and click Next.

<img width="1916" height="984" alt="image13" src="https://github.com/user-attachments/assets/7deace26-5339-499d-aaa3-8ffa9083d26b" />

6. Sign the message using the same login method you used to sign in:  
   * Web3 Wallet (Zelcore, MetaMask, SSP): Click the wallet icon to sign.  
   * Email Login: Click the Flux SSO/Email button.  
   * Once the Signature field auto-populates, click Next.

<img width="1919" height="989" alt="image18" src="https://github.com/user-attachments/assets/70011e19-9687-46ca-b064-fb11c7c60f85" />

7. Review the **Total Price \+ VAT**. Click **Register** to broadcast the signed message to the Flux network.  
   * If successful, you’ll see a green **DONE\!** and the message "*Registration Hash Received*".  
   * Click **Next**.


<img width="1916" height="988" alt="image20" src="https://github.com/user-attachments/assets/6778f235-b45c-4ec4-8551-3c09ff2dbe23" />

* 

8. Choose the payment method you want to use to pay for this app. We support **Stripe** (Card), **PayPal**, and **Flux**. Paying in Flux gives a 5% discount.

<img width="1918" height="989" alt="image4" src="https://github.com/user-attachments/assets/1e9c0ec0-8a80-44ee-9bb1-fb6efe0e4ebd" />

9. Once paid, click on **Done**, and then **Yes**.  Your TimpiCollector node will now deploy — typically within **10–30 minutes.**

---

### **Step 2: Configure Your Collector Node**

1. **Open Application Management**

   * In the left-hand menu, go to **Applications → Management**.

   * Under **My Active Apps**, locate your **Timpi Deployment**.

   * Click **Manage**, then confirm in the pop-up.

<img width="1917" height="987" alt="image17" src="https://github.com/user-attachments/assets/f5271e09-8ea4-4f85-bd77-06b96349477e" />

2. **Understand the Deployment Structure**

   * Your deployment runs on **three independent servers**, allowing you to operate up to **three Timpi Collector Nodes** from a single deployment.

   * Complete the configuration steps 3-5 below for all your server IPs of your deployment.

3. **Access the Running Instance**

   * On the management screen, go to the **Running Instances** tab (located under **Global App Management**).

   * Click the **App** button next to any server IP to open the node interface in a new browser tab.

<img width="1919" height="990" alt="image10" src="https://github.com/user-attachments/assets/65e8943a-31b0-4832-b808-2548eeee975b" />

4. **Configure the Node Settings**

   * In the node interface, click the **Settings** icon.

   * Enter your **Timpi Wallet Address** *(must hold a Timpi NFT)*.

   * Set the **Number of Workers** (1–5).

   * Click **Save**.

<img width="1558" height="938" alt="image5 (1)" src="https://github.com/user-attachments/assets/91e3f515-7e75-47ba-a2d1-c72e510469ac" />


5. **Start Indexing**

   * Return to the **Collector** tab in the node interface header.

   * Your node should now begin indexing pages.


<img width="1658" height="936" alt="image2 (1)" src="https://github.com/user-attachments/assets/44ca58a4-71af-4579-8e1d-b6d455ab7ef5" />



**Note:** Periodically check the server IPs, as they may rotate. Due to the nature of FluxCloud, if a server experiences downtime, the Collector Node may be redeployed to a new server with a different IP address. If this happens, simply repeat the steps above to configure the wallet address and number of workers via the Timpi Collector Node GUI on the new IP.

---

### **🔄 Updating Your App Subscription**

1. **Log in to FluxCloud**

   * Go to [home.runonflux.com](https://home.runonflux.com) and sign in.

2. **Access Your Application Management**

   * Navigate to **Applications → Management → My Active Apps**.

   * Find your **TimpiCollector** application.

   * Click **Manage**.

3. **Open the Update/Renew Tab**

   * Under **Global App Management**, go to the **Update/Renew** tab.

   * **Extend Subscription** will be toggled on by default.

   * Keep **Update Specifications** toggled **off**.

   * Select the **extension period** for your subscription.

   * Agree to the **Terms of Service** using the toggle.

   * Click **Compute Update Message**.

<img width="1916" height="988" alt="image11" src="https://github.com/user-attachments/assets/dd1c6010-6b0a-4bf5-9b75-4dc539665386" />


4. **Sign the Update Message**

   * Use the same sign-in method you used when registering the application:

     * **Web3 Wallet** (Zelcore, MetaMask, SSP): Click the wallet icon to sign.

     * **Email Login**: Click the **Flux SSO/Email** button.

   * Once the **Signature** field auto-fills, click **Update Application**.

<img width="1916" height="990" alt="image6" src="https://github.com/user-attachments/assets/74fba599-0207-4d7d-a52b-1fc2f9444351" />


5. **Complete Payment**

   * Scroll down to view payment options:

     * **Stripe** (Card)

     * **PayPal**

     * **Flux** (5% discount)

   * Complete payment.

   * Once payment is processed, you can leave the screen.

   * Your **TimpiCollector** node’s subscription period will update, typically within **10–30 minutes**.

<img width="1916" height="985" alt="image22" src="https://github.com/user-attachments/assets/97613910-a2ba-47a4-8777-3fa7bb5fff21" />


---

## **💻 Part 2: Deploying a Timpi Node via FluxEdge**

### **Step 1: Deploy a Timpi Synaptron Node**

1. Visit [https://console.fluxedge.ai](https://console.fluxedge.ai)

2. Sign in or sign up

<img width="1916" height="987" alt="image12" src="https://github.com/user-attachments/assets/c48a6647-940d-4b32-b284-bccc24733bdd" />


3. Navigate to the **Account Overview** using the left handed menu to deposit funds. We support PayPal, Credit Cards, or Flux. If you deposit via Flux you will receive a 5% bonus.

<img width="1606" height="932" alt="image14" src="https://github.com/user-attachments/assets/9e4c56b8-8dbe-4380-8339-0be696dc5bf2" />


4. Once your account is funded, click **Deploy App**, and on **Explore All Templates** at the Quick launch section.

5. Search for **Timpi Synaptron**, and click on it on the application

6. Read the README if you want to learn more about how the application works. Continue the deployment process by clicking on the **Builder** tab or **Continue** button to configure your application specifications.

<img width="1602" height="932" alt="image15" src="https://github.com/user-attachments/assets/418249c4-25fa-422f-87ba-2fa63c7a61ea" />


7. At **Environment Variables** enter both a **NAME** (min. 17 characters), and your **GUID** ([https://timpi.com/node/register](https://timpi.com/node/register))

   * Learn more on how to setup your **GUID** at  [Timpi Synaptron Linux Tutorial](https://github.com/Timpi-official/Nodes/blob/main/Synaptron/Tutorial/SynaptronLinux.md)

8. Adjust the resources as needed (or keep recommended)

<img width="1609" height="933" alt="image9" src="https://github.com/user-attachments/assets/6011c5b7-ba7b-4421-8a45-c31219680c26" />


9. Click the **Rent Machine** button to choose the machine you want to deploy your Timpi Synaptron node on. You can use filters like GPU model, location, or price range, or even **Advanced Filter** (RAM, storage, etc.) to choose a machine. You can also click a **Machine ID** to view details & reviews

<img width="1599" height="934" alt="image8" src="https://github.com/user-attachments/assets/07be5908-f10b-40a8-b7a0-b5227a3fb11e" />


13. Select the machine you want to rent and then click the **Rent** button, and confirm the deployment in the popup.

<img width="1040" height="771" alt="image21" src="https://github.com/user-attachments/assets/e7541468-b19a-4731-9d96-1a64f8e03ca8" />


You will get forwarded to your Synaptron Node deployment overview, where you will have access to all the necessary information of your application, like 

* URL, runtime, cost

* Access logs and shell

* Monitor events

<img width="1595" height="938" alt="image1" src="https://github.com/user-attachments/assets/59896e32-5d17-47ce-b345-bcff562cbe97" />


---

### **Step 2: Add Timpi Collector Nodes (Same Machine)** 

As you are already paying for the whole machine that your synaptron node is running on, it makes sense to use the unused resources of that machine to deploy further Timpi Collector Nodes on top of it. You can redo the below process and deploy **multiple Collector Nodes** alongside your Synaptron Node on the same machine.

Follow the steps below to get started:

1. On the machine overview, click the **three dots** on the machine row, where you have your Synaptron Node already running, then click **\+ New Deployment.**

2. Click on **Explore All Templates** at the Quick launch section, and search for **Timpi Collector**, and click on it. 

3. Read the README if you want to learn more about how the application works. Continue the deployment process by clicking on the **Builder** tab or **Continue** button to configure your application specifications.

4. Adjust resources, or keep them at recommended values, and click on the **Deploy App** button.

5. You will get forwarded to the **Deployment Overview** of your application. Wait until your application has the status running, and click the app URL link.

6. In the newly opened tab, click the **Settings icon**. Then enter your **Timpi Wallet address** (must hold a Timpi NFT), and set the Number **of Workers** from 1 to 5, and save it by clicking the **Save** button

<img width="1558" height="938" alt="image5 (1)" src="https://github.com/user-attachments/assets/7ee5798e-7b8e-4915-b45d-2cb9d529dfcf" />


7. Go back to the **Collector tab** in the header. Your node should now begin **indexing pages**

<img width="1658" height="936" alt="image2 (1)" src="https://github.com/user-attachments/assets/b86e19fd-7d37-417c-a581-ce3c16b82d4c" />

