|                          | |  |   |   |
| --------------------------------------- | -------- | ---------- |---------- |---------- |
| <a href="https://www.npmjs.com/package/react-native-dropdown-country-picker">![NPM VERSION](https://img.shields.io/npm/v/react-native-dropdown-country-picker?style=for-the-badge)</a> | <a href="https://www.npmjs.com/package/react-native-dropdown-country-picker">![NPM WEEKLY DOWNLOADS](https://img.shields.io/npm/dw/react-native-dropdown-country-picker?color=%232CA215&label=WEEKLY%20DOWNLOADS&style=for-the-badge)</a> | <a href="https://github.com/mmusaib/react-native-dropdown-country-picker/stargazers">![GITHUB STAR](https://img.shields.io/github/stars/mmusaib/react-native-dropdown-country-picker?label=Give%20Us%20A%20Star&style=for-the-badge)</a> | <a href="https://www.youtube.com/channel/UCSwIR2KBHiqiProH3Me8IZQ">![YOUTUBE VIEWS](https://img.shields.io/youtube/channel/views/UCSwIR2KBHiqiProH3Me8IZQ?label=YOUTUBE%20VIEWS&style=for-the-badge)</a> | <a href="https://www.npmjs.com/package/react-native-dropdown-country-picker">![NPM LIFETIME DOWNLOADS](https://img.shields.io/npm/dt/react-native-dropdown-country-picker?color=%232CA215&style=for-the-badge)</a>

<h1 align="center">
  🏳️‍🌈  React Native Skeleton Loading
</h1>

<div align="center">

🟢 React Native Dropdown Country Picker Similar as HTML Select List. It's not a modal. 

<a href="https://twitter.com/_mmusaib" target="_blank"></a>
<img src="https://i.imgur.com/sLjgFRR.gif" width="400" />
</div>



<h4>Light Weight and <b>Robust</b> Country Picker So Far.</h4>

-   Equivalent to React Native Stock Component
-   Use the styles of your choice
-   Search the countries seamlessly
-   Option to add customizable input mobile field next to the Picker
-   Zero dependencies



# Compatibility


|  iOS  | Android | Web | Expo |
--------|---------|-----|------|
|  ✅  |    ✅    | ✅ |  ✅  |




# 🔌 Installation

```sh
$ npm install react-native-dropdown-country-picker

```

OR

```sh
$ yarn add react-native-dropdown-country-picker
```


# 😎 Displaying the country picker
```jsx
import CountryCodeDropdownPicker from 'react-native-dropdown-country-picker'

const App = () => {
  const [selected, setSelected] = React.useState('+91');
  const [country, setCountry] = React.useState('');
  const [phone, setPhone] = React.useState('');

  return(
    <CountryCodeDropdownPicker 
        selected={selected} 
        setSelected={setSelected}
        setCountryDetails={setCountry} 
        phone={phone} 
        setPhone={setPhone} 
        countryCodeTextStyles={{fontSize: 13}}
      />
  )

};
```



For Live `Demo` [(Expo Snack)](https://snack.expo.dev/@mmusaib/react-native-dropdown-country-picker)

# ⭐ Props  for  the component
| Name | Type | Description | Default |
| ---- | ---- | ----------- | ----------- |
| selected | state var | The default selected country dial code stored in state variable | N/A
| setSelected | Function | setState function to set the selected state variable | N/A
| setCountryDetails | Function | setState function to set additional country details in respective state variable (Optional) | N/A
| phone | state var | state variable if you want to display phone number field  (Optional) | N/A
| setPhone | Funtion | setState function to set the phone state variable (Optional) | N/A
| countryCodeContainerStyles | style Object | style object to style the country code container (Optional) | N/A
| countryCodeTextStyles | style object | style object to style the text inside country code container (Optional) | N/A
| phoneStyles | style object | style object to style the text input of phone field (Optional) | N/A
| searchIcon | string | URL of the icon if you want to replace the search icon (Optional) | N/A
| closeIcon | string | URL of the icon if you want to replace the close icon (Optional) | N/A
| searchStyles | style object | style object to style the search input field (Optional) | N/A
| dropdownStyles | style object | style object to style the dropdown container (Optional) | N/A
| dropdownTextStyles | style object | style object to style the text inside dropdown container (Optional) | N/A






# ▶️ Watch Tutorial Video -->

 [![Watch video](https://i.imgur.com/QcWCHk9.png)](https://www.youtube.com/watch?v=ZstelmTWhjw)


<!-- For Live `Demo` [(Expo Snack)](https://snack.expo.dev/@mmusaib/react-native-stock-star-rating)









