<img alt="React Native Image Swiper" src="assets/logo.png" width="1050"/>

[![Battle Tested ✅](https://img.shields.io/badge/-Battle--Tested%20%E2%9C%85-03666e?style=for-the-badge)](https://github.com/WrathChaos/@freakycoder/react-native-image-swiper)

[![Fully customizable & extremely easy to use Image Swiper for React Native](https://img.shields.io/badge/-Fully%20customizable%20%26%20extremely%20easy%20to%20use%20Image%20Swiper%20for%20React%20Native-orange?style=for-the-badge)](https://github.com/WrathChaos/@freakycoder/react-native-image-swiper)

[![npm version](https://img.shields.io/npm/v/@freakycoder/react-native-image-swiper.svg?style=for-the-badge)](https://www.npmjs.com/package/@freakycoder/react-native-image-swiper)
[![npm](https://img.shields.io/npm/dt/@freakycoder/react-native-image-swiper.svg?style=for-the-badge)](https://www.npmjs.com/package/@freakycoder/react-native-image-swiper)
![Platform - Android and iOS](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue.svg?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg?style=for-the-badge)](https://github.com/prettier/prettier)

<p align="center">
  <img alt="React Native Image Swiper"
        src="assets/Screenshots/React-Native-Image-Swiper.gif" />
</p>

#### Take a look at [RN Image Gallery](https://github.com/Paraboly/react-native-image-gallery) for ready to use Image Swiper

# Installation

Add the dependency:

```bash
npm i @freakycoder/react-native-image-swiper
```

## Peer Dependencies

###### IMPORTANT! You need install them

```json
"react": ">= 16.x.x",
"react-native": ">= 0.55.x",
```

# Usage

## Import

```jsx
import ImageSwiper from "@freakycoder/react-native-image-swiper";
```

## Basic Usage

```jsx
<ImageSwiper
  imageHeight={700}
  onSwipeTop={() => alert("onSwipeTop")}
  onSwipeBottom={() => alert("onSwipeBottom")}
  images={[
    {
      uri:
        "https://images.unsplash.com/photo-1544550581-5f7ceaf7f992?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=958&q=80",
    },
    {
      uri:
        "https://images.unsplash.com/photo-1555149385-c50f336e28b0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=675&q=80",
    },
    {
      uri:
        "https://images.unsplash.com/photo-1532517891316-72a08e5c03a7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=701&q=80",
    },
  ]}
/>
```

# Configuration - Props

| Property       |   Type    |   Default    | Description                                                                                              |
| -------------- | :-------: | :----------: | -------------------------------------------------------------------------------------------------------- |
| images         |   array   |  undefined   | the main data of image swiper                                                                            |
| ImageComponent | component |    Image     | set your own Image component such as `FastImage`                                                         |
| onPageSelected | Function  |  undefined   | handle the selected page with this function                                                              |
| imageHeight    |  number   | ScreenHeight | change the image height                                                                                  |
| imageWidth     |  number   | ScreenWidth  | image width is changable but not recommended! You will broke the image swiper's horizontal swipe feature |
| onSwipeTop     | Function  |  undefined   | handle when the user swipe top on the image                                                              |
| onSwipeBottom  | Function  |  undefined   | handle when the user swipe bottom on the image                                                           |

## Future Plans

- [x] ~~LICENSE~~
- [x] ~~`initialPage` Feature~~
- [ ] Vertical Image Swiper Feature (Like Tiktok)
- [ ] Write an article about the lib on Medium

## Author

FreakyCoder, kurayogun@gmail.com

## License

React Native Image Swiper is available under the MIT license. See the LICENSE file for more info.
