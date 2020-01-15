# Hyper Protect Crypto Services Management Utilities

IBM Cloud™ Hyper Protect Crypto Services (Hyper Protect Crypto Services for short) is a dedicated key management service and hardware security module (HSM). It is designed to enable you to take control of your cloud data encryption keys and cloud hardware security modules, and is the only service in the industry built on FIPS 140-2 Level 4-certified hardware. For an introduction to the service, see [service overview](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-overview).

This repository contains the installation files of the two Management Utilities applications, the TKE client application and Smart card utility application, you need to set up the Hyper Protect Crypto Services Management Utilities.

## Provisioning the service
Follow [the instruction on service provisioning](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-provision) to provision a service instance of Hyper Protect Crypto Services in IBM Cloud.

## Initializing the service instance
After you provision a service instance, you need to initialize your service instance by loading the master key. You can choose to load the master key using the Management Utilities or from your workstation using the IBM Cloud Trusted Key Entry (TKE) CLI plug-in.

## Using the Management Utilities
If you need a highly secured environment to protect sensitive data and need to meet the highest level of security compliance requirements, [use the Management Utilities to initialize the service instance](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-initialize-hsm-management-utilities). To enable this solution, you need to use smart cards, which stores and encrypts the administrator signature key and master key parts, and provides hardware based protection. You also need additional devices such as the smart card readers, and additional applications such as the IBM Cloud Trusted Key Entry (TKE) client application and Smart card utility application so as to load the master key. For more information, see [Understanding the Management Utilities](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-introduce-service#understand-management-utilities).

For detailed instruction on how to set up the Management Utilities, including smart cards, smart card readers, TKE client application, and Smart card utility application, see [Setting up Management Utilities](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-prepare-management-utilities).
