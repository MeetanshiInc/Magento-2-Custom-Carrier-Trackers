# **Magento 2 Custom Carrier Trackers Extension**

Efficient order tracking is a cornerstone of a seamless shopping experience. With the **Magento 2 Custom Carrier Trackers Extension** by Meetanshi, merchants can simplify and personalize the shipping and tracking process, ensuring customers stay informed and satisfied.

This article delves into how the extension works, its features and how to set it up to enhance your Magento 2 store’s functionality.

## **How It Works**

The **Magento 2 Custom Carrier Trackers Extension** allows merchants to add and manage custom shipping carriers seamlessly. Instead of being limited to pre-configured carriers, you can configure any custom carrier and integrate it with your Magento 2 store. The extension also enables customers to track shipments directly through their accounts, improving transparency and trust.

## **Key Features**

* Send the tracking link directly to customers via email.  
* Automatically update tracking numbers and postcard details.  
* Hide the default tracking method to provide a tailored shipping experience.

## **Add Unlimited Custom Carriers**

This extension empowers merchants to integrate an unlimited number of custom carriers, catering to both local couriers and niche shipping providers, ensuring customers enjoy real-time shipment tracking. Merchants can effortlessly add carrier names, URLs and tracking formats, as well as modify or update carrier details directly from the Magento admin panel.

## **Improve Customer Experience with Easy Tracking**

Customers can easily access their shipment status and tracking details from the "My Orders" section of their accounts, with clear shipment information and clickable tracking URLs for quick and transparent updates.

## **Seamless Admin Interface**

Designed for user-friendliness, the extension allows admins to manage all custom carriers through a centralized dashboard, with simple configuration steps and an intuitive interface that ensures even non-technical users can operate it efficiently.

## **Extension Installation**

Follow these steps to install the **Magento 2 Custom Carrier Trackers Extension**:

### **Step 1:**

Extract the zip file and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 Custom Carrier Trackers Extension**

### **Step 1: Manage Custom Carrier Trackers**

![manage_custome_carrier_tracker](https://github.com/user-attachments/assets/7ffe1fee-179e-4234-8637-2cd0cfe30418)

The extension allows you to efficiently manage custom carrier trackers through the **Reports \> Manage Custom Carrier Trackers** grid. All previously added and saved carrier trackers are conveniently listed here for easy access and management.

### **Step 2: Add a New Tracker**

By clicking the **“Add New Tracker”** button in the **Manage Custom Carrier Trackers** grid, the admin can easily create a new carrier tracker.

![Add a New Tracker](https://github.com/user-attachments/assets/65fdd767-6542-488f-945a-c811d2e59b92)

* **Tracker Title**: Enter a custom title for the new tracker.  
* **Tracking URL**: Specify the tracking URL, utilizing custom variables to format the URL as needed.  
* **Status**: Activate the custom carrier tracker to make it available in the Configuration under the “Select Tracker” dropdown menu.

### **Step 3: Configure Settings**

To configure the extension, log in to Magento 2 and navigate to **Stores \> Configuration \> Meetanshi \> Custom Carrier Trackers**. Here, you can enable or disable the extension.

![Configure Settings](https://github.com/user-attachments/assets/a03d9f08-c382-43ac-acf8-a1e14ba6e3ce)

* **Custom Carrier Trackers**: Toggle to enable or disable the Custom Carrier Trackers extension.  
* **Custom Carrier Tracker 1**: The extension allows you to add and enable up to 10 custom carrier trackers.  
  * **Enable**: Set to **YES** to activate the custom carrier tracker.  
  * **Tracker Title**: Enter a custom title for the tracker.  
  * **Select Tracker**: Choose a custom carrier tracker from the list of added trackers in the **Manage Custom Carrier Trackers** grid. Select the appropriate tracker and save the configuration. You can enable up to 10 custom carrier trackers here.

### **Step 4: Adding a Tracking Number**

![Adding a Tracking Number](https://github.com/user-attachments/assets/a04adca5-38be-4313-aed4-c7d769ea0afa)

After an order is placed on the frontend, the admin must generate an invoice and shipment from the backend. During the shipment creation process, the admin can select a tracking carrier and assign a tracking number, allowing customers to track their orders.

### **Step 5: Custom Carrier Trackers in the Backend**

![Custom Carrier Trackers in the Backend](https://github.com/user-attachments/assets/5a43c2e4-9548-45be-a887-79805c544faa)

Once the tracking number is added, the shipment can be tracked from the backend. Simply click the **“Track”** button and it will display the tracking details in a separate window.

### **Step 6: Custom Carrier Trackers in the Frontend**

![Custom Carrier Trackers in the Frontend](https://github.com/user-attachments/assets/0a9f9589-ef0a-4d4e-99f5-c179de34ef8a)

Customers can track their shipments from the **“My Orders”** section. By clicking the **“Track this shipment”** link, they can view the tracking number and product details.

### **Step 7: Custom Carrier Trackers in Shipment Email**

![Custom Carrier Trackers in Shipment Email](https://github.com/user-attachments/assets/7a9066d0-754d-436b-b196-9aeebbbef542)

In addition to the **My Account** section, customers can track their shipments directly from the email by clicking on the tracking number.

## Download our [Magento 2 Custom Carrier Trackers](https://meetanshi.com/magento-2-custom-carrier-trackers.html) Extension
