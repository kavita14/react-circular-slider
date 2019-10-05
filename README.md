## React Circular Slider Component

### Installation

`npm install --save react-circular-slider`

### How To Use

First import this component where you want to use it

`import ReactCircularSlider from "react-circular-slider"`

Then just renders it

`<ReactCircularSlider />`

### Props

| _Prop_ |     _Description_     | _Default value_ |
| ------ | :-------------------: | :-------------: |
| color  | Sets background color |      blue       |
| width  |      Sets width       |       100       |
| height |      Sets height      |       100       |
| text   |    Sets inner text    |  empty string   |

### Example

```
import React, { Component } from "react";
import ReactCircularSlider from "react-circular-slider";

class App extends Component {
  render() {
    return (
        <ReactCircularSlider height={150} color="red" text="Hello World!" />
    );
  }
}

export default App;
```
