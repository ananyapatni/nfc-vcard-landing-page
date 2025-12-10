# **APS Sales – NFC vCard Landing Page**

This repository contains the official source code for the **APS Sales NFC vCard Landing Page**.
The landing page is designed to serve as a digital business card that can be accessed via NFC cards, QR codes, or direct URL entry. It is optimized for mobile devices and is deployed using GitHub Pages with the custom domain **apsales.in**.



## **Live Website**

**[https://apsales.in](https://apsales.in)** or **https://ananyapatni.github.io/apsales.in/**



## **Overview**

The project provides a clean and fast-loading static webpage intended to represent APS Sales professionally across digital and physical touchpoints. The implementation uses a lightweight HTML structure to ensure broad compatibility and seamless performance on all devices.



## **Features**

* **Mobile-first design:** Optimized for smartphones and NFC-based interactions.
* **Lightweight implementation:** Pure HTML/CSS for maximum speed and minimum overhead.
* **Brand-aligned visual layout:** Incorporates APS Sales branding assets.
* **GitHub Pages integration:** Automatically deployed from the `main` branch.
* **Custom domain support:** Configured to operate under the domain **apsales.in** with HTTPS enabled.



## **Repository Structure**

```
apsales.in/
│
├── index.html                 # Primary webpage served at apsales.in
├── apsales logo.jpg           # Branding asset used in the landing page
├── CNAME                      # Custom domain configuration for GitHub Pages
├── LICENSE                    # MIT License for open-source usage
├── README.md                  # Project documentation
└── .github/
    └── workflows/             # Deployment workflow for GitHub Pages
```

## **Deployment**

Deployment is handled automatically through GitHub Pages:

* The `main` branch is the active deployment source.
* Changes pushed to `main` trigger a new build and publishing process.
* The `CNAME` file ensures that the site resolves correctly at **apsales.in**.

No manual deployment steps are required.


## **Custom Domain Configuration**

The repository is configured to use the custom domain:

```
apsales.in
```

DNS records and GitHub Pages settings have been aligned to ensure consistent HTTPS access.
If the domain configuration changes in the future, the `CNAME` file must be updated accordingly.


## **License**

This project is released under the **MIT License**.
You may use, modify, and distribute the code in accordance with the license terms.


