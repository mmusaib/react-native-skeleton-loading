|                          | |  |   |   |
| --------------------------------------- | -------- | ---------- |---------- |---------- |
| <a href="https://www.npmjs.com/package/react-native-skeleton-loading">![NPM VERSION](https://img.shields.io/npm/v/react-native-skeleton-loading?style=for-the-badge)</a> | <a href="https://www.npmjs.com/package/react-native-skeleton-loading">![NPM WEEKLY DOWNLOADS](https://img.shields.io/npm/dw/react-native-skeleton-loading?color=%232CA215&label=WEEKLY%20DOWNLOADS&style=for-the-badge)</a> | <a href="https://github.com/mmusaib/react-native-skeleton-loading/stargazers">![GITHUB STAR](https://img.shields.io/github/stars/mmusaib/react-native-skeleton-loading?label=Give%20Us%20A%20Star&style=for-the-badge)</a> | <a href="https://www.youtube.com/channel/UCSwIR2KBHiqiProH3Me8IZQ">![YOUTUBE VIEWS](https://img.shields.io/youtube/channel/views/UCSwIR2KBHiqiProH3Me8IZQ?label=YOUTUBE%20VIEWS&style=for-the-badge)</a> | <a href="https://www.npmjs.com/package/react-native-skeleton-loading">![NPM LIFETIME DOWNLOADS](https://img.shields.io/npm/dt/react-native-skeleton-loading?color=%232CA215&style=for-the-badge)</a>

<h1 align="center">
  🏳️‍🌈  React Native Skeleton Loading
</h1>

<div align="center">

🟢 Skeleton Loading Component for Expo and React Native powered apps 

<a href="https://twitter.com/_mmusaib" target="_blank"></a>
<img src="https://i.imgur.com/sLjgFRR.gif" width="400" />
</div>



<h4>Light Weight and <b>Robust</b> Skeleton Loader.</h4>

-   Design skeleton loading screen of your choice 
-   Pass colors of your choice
-   Powered by Reanimated 3
-   Make your apps professional in UI/UX




# Compatibility


|  iOS  | Android | Expo |
--------|---------|------|
|  ✅  |    ✅    |  ✅  |




# 🔌 Installation

```sh
$ npm install react-native-skeleton-loading

```

OR

```sh
$ yarn add react-native-skeleton-loading
```


# 😎 Displaying the skeleton loading
All you need is to just import the skeleton loading component, and in between the
closing and ending tags, you can design the UI of your skeleton loading screen
as shown in the code snippet below:

```jsx
import SkeletonLoading from 'react-native-skeleton-loading'

const App = () => {

  return(
    <SkeletonLoading background={ 'lightgrey' } highlight={ 'white' }>
      <View style={{ flexDirection: 'row', justifyContent: 'space-between' }}>
          <View style={{ width: "20%", height: "14%", backgroundColor: 'lightgrey', borderRadius: 10 }} />

          <View style={{ flex:1 }}}>
              <View style={{ backgroundColor: 'lightgrey', width: "50%", height: 10, marginBottom: 3, borderRadius: 5 }} />
              <View style={{ backgroundColor: 'lightgrey', width: '20%', height: 8, borderRadius: 5 }} />
          </View>
      </View>
    </SkeletonLoading>
  )

};
```



For Live `Demo` [(Expo Snack)](https://snack.expo.dev/@mmusaib/react-native-skeleton-loading)

# ⭐ Props  for  the component
| Name | Type | Description |
| ---- | ----------- | ----------- |
| background | hex color string | Hex color string for the background of loading component
| highlight | hex color string | Hex color string for the highlight of loading component







<!-- # ▶️ Watch Tutorial Video 

 [![Watch video](https://i.imgur.com/QcWCHk9.png)](https://www.youtube.com/watch?v=ZstelmTWhjw) -->


<!-- For Live `Demo` [(Expo Snack)](https://snack.expo.dev/@mmusaib/react-native-stock-star-rating)









