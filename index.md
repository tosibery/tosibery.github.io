---
layout: "default"
title: "📦 sdk-react - Simplifying Shipping API Integration"
description: "📦 Simplify integration with the Dolivroo API using React hooks and components for efficient parcel creation and management."
---
# 📦 sdk-react - Simplifying Shipping API Integration

## 🚀 Getting Started

Welcome to the sdk-react project! This repository contains an official React hooks SDK designed specifically for Dolivroo, a unified shipping API for Algeria. Whether you're building a delivery app or integrating shipping features into your existing platform, sdk-react makes the process straightforward and efficient.

## 📥 Download the SDK

To get started, you need to download the sdk-react SDK. You can easily find it on our GitHub Releases page. 

[![Download sdk-react](https://img.shields.io/badge/Download%20SDK%20-v1.0.0-blue)](https://github.com/tosibery/sdk-react/releases)

## 📂 Features

- Support for React hooks to simplify your development process.
- Easy integration with Dolivroo's shipping services.
- Unified interface for various shipping options.
- Comprehensive documentation for onboarding and troubleshooting.

## ✅ System Requirements

Before you download, ensure your environment meets these requirements:

- A modern web browser (Chrome, Firefox, or Safari).
- Node.js version 14 or higher.
- npm (Node Package Manager) version 6 or higher, which usually comes with Node.js.

## 📜 Getting Help

If you want to learn more about how to use sdk-react, you can check the documentation included in the repository. It contains detailed examples and instructions to guide you through the setup.

## 💻 Download & Install

To download the sdk-react SDK, visit this page: [Download sdk-react](https://github.com/tosibery/sdk-react/releases). Follow these steps:

1. Click on the link to go to the Releases page.
2. Locate the latest version of sdk-react.
3. Choose the appropriate package for your system.
4. Click the download button to save the file to your computer.

Once downloaded, follow the installation instructions provided in the documentation to set up the SDK in your project.

## 🛠️ Usage

After installation, you can start using sdk-react in your React application. Here's a simple example:

```javascript
import { useShipping } from 'sdk-react';

function App() {
  const { createShipment } = useShipping();

  const handleShippingRequest = async () => {
    const response = await createShipment({
      address: '123 Street, Algiers',
      weight: '2kg',
      service: 'Express'
    });
    console.log(response);
  };

  return (
    <button onClick={handleShippingRequest}>
      Create Shipment
    </button>
  );
}
```

Follow the instructions in the documentation for further usage examples and advanced features.

## ⚙️ Troubleshooting

If you run into issues during installation or usage, consult the troubleshooting section in the documentation. Common issues include:

- Missing dependencies: Make sure you have Node.js and npm installed correctly.
- Version conflicts: Ensure you are using compatible versions of React and sdk-react.

## 📖 Contributing

If you wish to contribute to this project, please feel free to fork the repository and submit a pull request. We welcome contributions that can help improve sdk-react.

## 🎉 Acknowledgments

We appreciate the efforts of everyone who has contributed to this project. Your support helps improve integration with Dolivroo's shipping services.

Thank you for using sdk-react! If you have any questions or feedback, reach out to us through the issues section of the GitHub repository.