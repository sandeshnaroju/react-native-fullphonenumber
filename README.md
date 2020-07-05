# react-native-fullphonenumber
This is code for full phone number input (with country code). No need to use third party Libraries. 

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
