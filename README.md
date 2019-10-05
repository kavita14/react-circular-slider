React circular Slider Component
Installation
npm install --save react-circular-slider

How To Use
First import this component where you want to use it

import ReactCircularSlider from "react-circular-slider"

Then just renders it

<ReactCircularSlider />

Props
Prop	Description	Default value
color	Sets background color	blue
width	Sets width	100
height	Sets height	100
text	Sets inner text	empty string
Example
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
