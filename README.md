Technology The following are the key technologies and tools used in the development of this project:

Mobile React Native: It's a mobile app development framework that allows you to build native apps for iOS and Android using JavaScript and React. It enables mobile app development with a single codebase, providing a native user experience. Expo: It's an open-source platform and set of tools for building native mobile apps using JavaScript and React Native. Expo provides a range of ready-to-use components and APIs that streamline app development, including access to features like camera, geolocation, and push notifications. Nativewind: NativeWind uses Tailwind CSS as scripting language to create a universal style system for React Native. NativeWind components can be shared between platforms and will output their styles as CSS StyleSheet on web and StyleSheet.create for native. Axios: Is a simple promise based HTTP client for the browser and node.js. Axios provides a simple to use library in a small package with a very extensible interface. Zustand: Is a minimalist state management library for React applications. It offers a simple and intuitive API for managing application state, with support for global state, local state, and derived state. Zustand emphasizes simplicity, performance, and ease of use. Async Storage: Is a library for React Native that provides a simple asynchronous storage system for persisting key-value data in the app's local storage. It offers a straightforward API for storing, retrieving, and deleting data, making it easy to manage app state across sessions. Async Storage is commonly used for caching data, storing user preferences, and implementing offline functionality in mobile applications. Expo Image Picker: Is a library that enables developers to easily add image selection functionality to their Expo projects. With this library, users can choose images from their device's gallery or take photos using the device's camera. Moti: Is a declarative animations library for React Native that allows developers to create smooth and interactive animations with ease. It provides a simple API for defining animations using JavaScript syntax, making it straightforward to add motion to your app's UI elements. React Native Reanimated: I s a powerful animation library for React Native that provides a low-level API for building complex and high-performance animations. It allows developers to create fluid and responsive animations by directly manipulating the native animation drivers on the UI thread. React Native QRCode Svg: Is a library for generating QR codes in React Native applications using SVG (Scalable Vector Graphics). It allows developers to easily create QR codes from data strings and customize their appearance using SVG properties such as color, size, and style. Server NodeJS: Is a JavaScript runtime built on Chrome's V8 JavaScript engine.

Fastify: Is a web framework highly focused on providing the best developer experience with the least overhead and a powerful plugin architecture.

Prisma: Is a next-generation ORM that consists of these tools:

Prisma Client: Auto-generated and type-safe query builder for Node.js & TypeScript Prisma Migrate: Declarative data modeling & migration system Prisma Studio: GUI to view and edit data in your database Zod: Is a TypeScript-first schema declaration and validation library. I'm using the term "schema" to broadly refer to any data type, from a simple string to a complex nested object.

How It Works Create Ticket (QR Code): Allows users to generate a unique QR code ticket only if no credential has been created for that email address.

Remove Ticket (QR Code): Enables users to remove a QR code ticket from the system while retaining the ability to access it later.

Get Ticket (QR Code) by Code: Allows users to retrieve a QR code ticket using its corresponding code.

Installation

Clone the repository and follow the steps below:

Mobile Install the dependencies:

cd mobile npm install Start the web:

npx expo start Scan the QR code using the Expo Go app on your mobile device or use an emulator to test the app.

Server Install the dependencies:

cd server npm install Start the server:

npm run dev
