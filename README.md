# React Text Morpher 
React Text Morpher is a react commponent which morphered over multi texts.

[Here](https://user-images.githubusercontent.com/63685461/115680850-e950c400-a38e-11eb-835e-cd49a4816d74.mp4)
is  an example.

It is awesome, isn't it?

## Installation

Run 

```
git clone https://github.com/ozora-ogino/react-text-morpher
```

## Usage 

Here's how to use React Text Mopher.

You need to give 2 parameters to the component.

1. texts

    js dictionary which include "text" for first text and words for words you want to use to transform.

2. elements

    You can choose from h1, h2, h3, h4 or p.

### Example

```JavaScript
import Mohpher from "./react-text-mopher/index";

const texts = {
  text: "example",
    words: [
      "例子",
      "例",
      "예",
      "edæmi",
      "esempio",
      "exemplu",
      "उदाहरण",
      "пример",
    ],
  }
export default = () => {
     
    <Morpher texts={texts} element="h1"/>

}
```

## Contribution

Contribution is more than welcome.