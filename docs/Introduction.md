**[Demo](https://santiagocasasrey.github.io/tabler-react/)**

## Install

Make sure you have [Node.js](https://nodejs.org/) 8+ and [yarn](https://yarnpkg.com) installed.

`npm install santiagocasasrey/tabler-react`

## Basic Usage Example

```jsx static
import React, { Component } from "react";

import "tabler-react/dist/Tabler.css";

import { Card, Button } from "tabler-react";

class MyCard extends Component {
  render() {
    return (
      <Card>
        <Card.Header>
          <Card.Title>Card Title</Card.Title>
        </Card.Header>
        <Card.Body>
          <Button color="primary">A Button</Button>
        </Card.Body>
      </Card>
    );
  }
}
```
