# react-native-fullphonenumber
This is code for full phone number input (with country code). It depends on Popular [react-native-elements](https://react-native-elements.github.io/react-native-elements/docs/getting_started.html) project.

## HOW TO USE

Just download `FullPhoneNumber.js` file along with `countryCodes.json`. And use it like this

```
<FullPhoneNumber
     onChangeText={(text)=>{
          console.log(text)
     }}
     errorMessage=''
     />
```

You can Change the path of the `countryCodes.json` in `componentDidMount` method in `FullPhoneNumber.js`.
