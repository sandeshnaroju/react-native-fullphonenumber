# react-native-fullphonenumber
This is code for full phone number input (with country code) with search feature. It depends on Popular [react-native-elements](https://react-native-elements.github.io/react-native-elements/docs/getting_started.html) project.

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

You can change the path of the `countryCodes.json` in `componentDidMount` method in `FullPhoneNumber.js`.

#### Preview screenshots

##### 1

<img src="https://github.com/sandeshnaroju/react-native-fullphonenumber/blob/master/fullPhoneNumber1.jpg" width="250">

##### 2

<img src="https://github.com/sandeshnaroju/react-native-fullphonenumber/blob/master/fullPhoneNumber2.jpg" width="250">

##### 3

<img src="https://github.com/sandeshnaroju/react-native-fullphonenumber/blob/master/fullPhoneNumber3.jpg" width="250">

##### 4

<img src="https://github.com/sandeshnaroju/react-native-fullphonenumber/blob/master/fullPhoneNumber4.jpg" width="250">




