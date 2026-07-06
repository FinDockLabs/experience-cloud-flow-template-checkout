# Experience Cloud Checkout Flow

## Deploy
[![Deploy to Salesforce](https://app.jdeploy.cloud/images/flat.svg)](https://app.jdeploy.cloud/github/FinDockLabs/experience-cloud-flow-template-checkout/main)

## Description

This repository contains a Flow template to help you get started with building digital payment experiences using Experience Cloud and FinDock Payment Experiences. The **Checkout Flow** is designed for commercial use cases such as invoices, subscriptions, memberships and recovering failed payments.

This template is meant to be customized and extended to fit specific use cases and requirements. For other options, see [Templates for FinDock Payment Experiences](https://github.com/FinDockLabs/experience-cloud-templates). 

**Key features**

* Collect new one-time payments  
* Set up new recurring donations  
* Pay existing one-time payments  
* Update existing recurring payments  
* Supports multiple currencies

## Prerequisites

* FinDock is installed and configured.  
* FinDock is the source of payments data ([FinDock Standalone](https://docs.findock.com/docs/source-connectors/findock-standalone)).  
* At least one payment extension is installed and configured.  
* Digital Experiences is enabled in the org.

## Installation
1. Press the button below to deploy the templates to your org.  
2. Follow [these instructions](https://help.salesforce.com/s/articleView?id=experience.rss_flow_guestuser.htm&type=5) to set up guest user access for the flows.  
3. Open the Checkout Flow in the Flow editor, go to the Pay Screen element, and configure [payment method selection](https://docs.findock.com/docs/july-26/payments/payment-method-selector).  
4. Go to the Payment Screen element and configure the [payment intent](https://docs.findock.com/docs/july-26/payments/pay-button) (add at least a success and failure URLs and verify the mapping matches your use case).  
5. Under Assign Example Variables, enter a valid contact Id or change the assignments to fit your use case.  
6. Activate your flow.  
7. Go to the Experience Cloud Administration -> Preferences and enable "Allow guest users to access public APIs.”  
8. Add the flow to your Experience Cloud site.
