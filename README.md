# Information Management App


[![NPM](https://img.shields.io/npm/v/stream-chat-react.svg)](https://www.npmjs.com/package/stream-chat-react)
[![build](https://github.com/GetStream/stream-chat-react/workflows/test/badge.svg)](https://github.com/GetStream/stream-chat-react/actions)
[![Component Reference](https://img.shields.io/badge/docs-component%20reference-blue.svg)](https://getstream.io/chat/docs/sdk/react/)
[![codecov](https://codecov.io/gh/GetStream/stream-chat-react/branch/master/graph/badge.svg)](https://codecov.io/gh/GetStream/stream-chat-react)

<img align="right" src="https://getstream.imgix.net/images/chat/chattutorialart@3x.png?auto=format,enhance" width="50%" />


The SRS document outline has four parts:

- Introduction
- Functional requirement
- Production structure


## Introduction

The information management production is an application that
users can save or share documents including interview questions, job posts, experiences, skill assessments, and something else in a group or private channel.

### `Product scope`
The multiple teams or users that are authorized will have access to the document.

The document manager accept users or team's request and allows to access to the documents.
### `Product value, Intended use`
Collaborate with team to gather or share documents including interview questions, job pots, experiences, skill assessments and provide regular updates on the database.



## System requirements and functional requirements

### `Authtication`
Authorization is a process by which a server determines if the client has permission to use a resource or access documents.

Register function: the server accepts new users' requests.

Login function:  the server allows authorized users access to documents.

### `Documents View, inserts, remove`
Sort function: sorts the documents by updated date.

Search function: search documents by filter(date, username, keywords)

Insert function: the authorized user can inserts documents

Remove function: the authorized user can delete documents
## Production Structure

### `Register/Login components: `
- The component should include name field, gmail field, password field in register panel
- The component should include name field, gmail field, password field in login pannel

### `Dashboard component`
- A list of documents fields on the right side of screen.
- A center panel that displays the messages for the currently focused chat group.
- A Search filter at the top of the center panel.
- Thelist of documents fields should display the name and nomber of unreads documents for the each field.
- The center panel should display the documents for the currently focused field, with the most recent documents au the top default.
- The application should have appropriate error handling and display user-friendly error messages in the case of any issues

## Installation

### Install with NPM

`npm install`

## Docs


##  TypeScript Support

As of version `5.0.0`, the component library has been converted to TypeScript. Please read the [TypeScript guide](https://github.com/GetStream/stream-chat-react/wiki/Typescript-support) for details and implementation assistance.

##  Component Reusability

### Customizing Styles

The preferred method for overriding the pre-defined styles in the library is to two step process. First, import our bundled CSS into the file where you instantiate your chat application. Second, You can then add selectors to your local CSS file to override our defaults. For example:

```js
import './style.css';
import './App.css';
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More
