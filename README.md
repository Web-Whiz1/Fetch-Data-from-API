# Fetch Data from API

## Overview

This is a simple React component that fetches data from a public API (JSONPlaceholder) and displays a list of posts. The component demonstrates how to use the `useEffect` and `useState` hooks to manage asynchronous data fetching and loading states.

## Features

- Fetches data from a public API (`https://jsonplaceholder.typicode.com/posts`)
- Displays loading state while data is being fetched
- Renders a list of titles from the fetched data

## Installation

To use this component in your project, follow these steps:

1. Clone this repository or copy the component files to your React project.
2. Install any necessary dependencies (if applicable).
3. Import the `FetchData` component into your application.
```bash
import FetchData from './path/to/FetchData';
```
4.Use the component in your application:
```jsx
<FetchData />
```

## Example Usage

Here is a basic example of how to use the `FetchData` component in your application:

```jsx
import React from 'react';
import FetchData from './FetchData';

function App() {
  return (
    <div>
      <h1>My Application</h1>
      <FetchData />
    </div>
  );
}

export default App;
```
##### Usage
When you use the FetchData component, it will automatically fetch the data when the component mounts. The titles of the posts will be displayed in a list format. If the data is still loading, a loading message will be shown.

License
This project is open-source and available under the MIT License.

Acknowledgments
The data for this project is provided by JSONPlaceholder, a free online REST API that you can use whenever you need some fake data.
