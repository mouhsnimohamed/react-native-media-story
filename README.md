# React Native Stories Media ⚡

[![npm version](https://img.shields.io/npm/v/react-native-stories-media.svg)](https://www.npmjs.com/package/react-native-stories-media)
![Platform - Android and IOS](https://img.shields.io/badge/platform-Android%20%7C%20IOS-green.svg)

![](assets/storybg.jpeg)
<br>

A simple and fully customizable React Native components that provides a status/stories feature like Whatsapp, Instagram. For navigation across all the stories you can touch the left or right portion of the screen similar to what we see on Whatsapp or Instagram. The library works seemleslly across both Android as well as IOS platform developed with ❤️ in <b>Typescript & React</b> 🔥.

#### Feature's include :

- Video in portrait and landscape
- Read more with webview
- Progress bar with custom duration & styling options.
- A fully customizable Header View, you can use default one or pass in your choice of component.

<br>

## Spread Your ❤️:

[![GitHub followers](https://img.shields.io/github/followers/iguilhermeluis.svg?style=social&label=Follow)](https://github.com/iguilhermeluis) [![Twitter Follow](https://img.shields.io/twitter/follow/gldesenvolvedor.svg?style=social)](https://twitter.com/gldesenvolvedor)
<br>

## Demo

 <img src='https://github.com/mouhsnimohamed/react-native-media-story/blob/main/demo/demo.gif?raw=true' height=480 width=270 />

<br>

## Screenshots

| Example One           | Example Two           | Example Three         | Example Four          | Example Five          |
| --------------------- | --------------------- | --------------------- | --------------------- | --------------------- |
| ![](demo/screen0.png) | ![](demo/screen4.png) | ![](demo/screen2.png) | ![](demo/screen5.png) | ![](demo/screen3.png) |

<br>

## Installation

If using yarn:

```
yarn add react-native-stories-media
```

If using npm:

```
npm i react-native-stories-media
```

<br>

## Usage

For example code, <a href='https://github.com/mouhsnimohamed/react-native-media-story/blob/main/demo/index.tsx'><b>Click here</b></a>

#### Basic Usage

```js
import React from "react";
import { View } from "react-native";
import Stories from "react-native-stories-media";

const data = [
  {
    username: "Jacob",
    profile:
      "https://images.unsplash.com/profile-1531581190171-0cf831d86212?dpr=2&auto=format&fit=crop&w=150&h=150&q=60&crop=faces&bg=fff",
    title: "News",
    stories: [
      {
        id: 1,
        url:
          "https://images.unsplash.com/photo-1512101176959-c557f3516787?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60",
        type: "image",
        duration: 2,
        isReadMore: true,
        url_readmore: "https://www.mouhsni.com",
        created: "2021-01-07T03:24:00",
      },
      {
        id: 2,
        url:
          "https://images.unsplash.com/photo-1478397453044-17bb5f994100?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60",
        type: "video",
        duration: 2,

        isReadMore: true,
        url_readmore: "https://www.mouhsni.com",
        created: "2021-01-07T03:24:00",
      },
      {
        id: 3,
        component: <MyComponent />
        type: "view",
        duration: 2,
        created: "2021-01-07T03:24:00",
      },
    ],
  },
];

export default function Demo() {
  return (
    <View style={{ flex: 1, paddingVertical: 20 }}>
      <Stories data={data} />
    </View>
  );
}
```

## About Me

## Guilherme Luis Faustino

_Hi, I'm Guilherme Luis. I've been working as Front-End Developer since 2009. I'm passionate about open source projects, I believe that the dissemination of knowledge and good ideas inspires and improves the world._

For more exciting updates follow me,

[![Twitter Follow](https://img.shields.io/twitter/follow/gldesenvolvedor.svg?style=social)](https://twitter.com/gldesenvolvedor)
