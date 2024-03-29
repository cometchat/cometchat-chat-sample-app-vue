# Vue Sample App by CometChat

This is a reference application showcasing the integration of [**CometChat's Vue UI Kit**](https://www.cometchat.com/docs/v4/vue-uikit/overview) within an Vue framework. It provides developers with examples of implementing real-time messaging and voice and video calling features in their own Vue-based applications.

## Prerequisites

- Ensure that you have Node.js and npm installed:

    ```sh
    npm install npm@latest -g
    ```

- Sign up for a [CometChat](https://app.cometchat.com/) account to get your app credentials: _`App ID`_, _`Region`_, and _`Auth Key`_


## Installation
1. Clone the repository:
    ```
    git clone https://github.com/cometchat-pro/cometchat-sample-app-vue.git
    ```
2. Navigate to the cloned directory:
    ```
    cd cometchat-sample-app-vue
    ```
3. Install dependencies:
    ```
    npm install
    ```
4. Enter your CometChat _`App ID`_, _`Region`_, and _`Auth Key`_ in the [src/AppConstants.ts](https://github.com/cometchat/cometchat-sample-app-vue/blob/v4/src/AppConstants.ts) file:
    ```typescript
    export const AppConstants = {
    APP_ID: "APP_ID",
    REGION: "REGION",
    AUTH_KEY: "AUTH_KEY",
    };
    ```
5. Run the project locally to see all CometChat features in action:
    ```
    npm run serve
    ```
![HomeScreen](./Screenshots/HomeScreen.png)


## Help and Support
For issues running the project or integrating with our UI Kits, consult our [documentation](https://www.cometchat.com/docs/vue-uikit/integration) or create a [support ticket](https://help.cometchat.com/hc/en-us) or seek real-time support via the [CometChat Dashboard](http://app.cometchat.com/).
