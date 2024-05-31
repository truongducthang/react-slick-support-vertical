### react-slick-support-vertical

[![Backers on Open Collective](https://opencollective.com/react-slick-support-vertical/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/react-slick-support-vertical/sponsors/badge.svg)](#sponsors)

##### Carousel component built with React. It is a react port of [slick carousel](http://kenwheeler.github.io/slick/)

## [Documentation](http://react-slick-support-vertical.neostack.com)

### Installation

**npm**

```bash
npm install react-slick-support-vertical --save
```

**yarn**

```bash
yarn add react-slick-support-vertical
```

**Also install slick-carousel for css and font**

```bash
npm install slick-carousel

// Import css files
import "slick-carousel/slick/slick.css";
import "slick-carousel/slick/slick-theme.css";
```

or add cdn link in your html

```html
<link
  rel="stylesheet"
  type="text/css"
  charset="UTF-8"
  href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css"
/>
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.min.css"
/>
```

### [PlayGround](https://stackblitz.com/edit/vitejs-vite-ownrun?file=src%2FImageSlider.jsx)

### Example

```js
import React from "react";
import Slider from "react-slick-support-vertical";

export default function SimpleSlider() {
  var settings = {
    dots: true,
    infinite: true,
    speed: 500,
    slidesToShow: 1,
    slidesToScroll: 1
  };
  return (
    <Slider {...settings}>
      <div>
        <h3>1</h3>
      </div>
      <div>
        <h3>2</h3>
      </div>
      <div>
        <h3>3</h3>
      </div>
      <div>
        <h3>4</h3>
      </div>
      <div>
        <h3>5</h3>
      </div>
      <div>
        <h3>6</h3>
      </div>
    </Slider>
  );
}
```

### Props

For all available props, go [here](https://react-slick-support-vertical.neostack.com/docs/api/).

### Methods

For all available methods, go [here](https://react-slick-support-vertical.neostack.com/docs/api#methods)

### Development

Want to run demos locally

```bash
git clone https://github.com/truongducthang/react-slick-support-vertical
cd react-slick-support-vertical
npm install
npm start
open http://localhost:8080
```

## Community

Join our [discord channel](https://discord.gg/z7stRE4Cyb) to discuss react-slick-support-vertical bugs and ask for help

## Contributing

Please see the [contributing guidelines](./CONTRIBUTING.md)
