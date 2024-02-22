# JavaScript SDK: Streamline Your Backend Experience
![JavaScript SDK logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png

Welcome to **JavaScript SDK**! This project is a versatile JavaScript library specifically designed to make working with a Framework backend a breeze. It simplifies database management, file uploads, API calls, and user authentication, helping you focus on what matters most - building amazing applications!

Explore our official [website](https://empress.eco/) or visit the [documentation](https://grow.empress.eco/) to get started. For [bug reporting](https://github.com/empress-eco/javascript_sdk/issues) or [feature requests](https://github.com/empress-eco/javascript_sdk/issues), click on the respective links.

## About The Project

### 📖 Overview

JavaScript SDK is a TypeScript/JavaScript library that bridges the gap between developers and the Framework backend. It provides an easy-to-use interface for managing database operations, handling file uploads, making API calls, and performing user authentication.

### 🌟 Key Features

- 🔐 **Authentication**: Supports both cookie-based and token-based authentication.
- 🗄 **Database**: Easily manage your documents - Get, update, create, delete, fetch lists and counts.
- 📄 **File Upload**: A straightforward file upload function.
- 🤙🏻 **API Calls**: API calls made easy.

The library uses [Axios](https://axios-http.com) under the hood to make API calls to your backend, ensuring performance and reliability.

## Technical Stack and Setup Instructions

JavaScript SDK utilizes modern technologies like TypeScript and Axios. To get started, you need to have either npm or yarn installed on your system. 

### Installation

Clone the repository using the following command:

```bash
git clone https://github.com/empress-eco/javascript_sdk.git
```

Install the JavaScript SDK library using npm:

```bash
npm install Empress-js-sdk
```

or yarn:

```bash
yarn add Empress-js-sdk
```

## Usage

Once installed, you can initialize the library as follows:

```js
import { EmpressApp } from 'Empress-js-sdk';
// Add your backend's URL
const Empress = new EmpressApp('https://test.Empress.cloud');
```

For token-based authentication (OAuth bearer tokens or API key/secret pairs), initialize the library like this:

```js
import { EmpressApp } from "Empress-js-sdk";

const Empress = new EmpressApp("https://test.Empress.cloud", {
    useToken: true,
    // Pass a custom function that returns the token as a string
    token: getTokenFromLocalStorage(),
    // This can be "Bearer" or "token"
    type: "Bearer"
})
```

The library offers numerous functions for database operations, user authentication, API calls, and file uploads. Refer to the [official documentation](https://grow.empress.eco/) for detailed instructions.

## Contribution Guidelines

We welcome and appreciate contributions from the community. Whether it's a bug fix, new feature, or a small tweak, your contribution matters! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

Before submitting a pull request, please ensure your code adheres to our coding standards and the tests pass.

## License and Acknowledgements

This project is licensed under the terms of the MIT license. For more information, see [LICENSE](./LICENSE).

Special thanks to the Empress Community for their foundational contributions to this project. Their innovation and dedication have been instrumental in building the tools we rely on, and we are profoundly grateful for their pioneering work and ongoing support.

Finally, a huge shoutout to our dedicated maintainers, Nikhil Kothari, Janhvi Patil, and Sumit Jain. Their dedication and hard work keep JavaScript SDK running smoothly. You can follow them on [Github](https://github.com/empress-eco/) and Twitter for updates and insights.