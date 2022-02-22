<img src="https://user-images.githubusercontent.com/31222514/149813755-3f74a208-1e4c-4d81-b848-1d4f1a18b969.png" width="10%" alt="React logo">

# React Native

## Setup

Install tooling
```bash
$ npm install -g expo-cli
```
Init project
```bash
$ expo init <project_name>
```
Run it
```bash
$ npm start
```

## Main components

- `<View>` - like `div` ([see here](https://reactnative.dev/docs/view))
- `<ScrollView>` - like `div` that you can scroll ([see here](https://reactnative.dev/docs/scrollview))
- `<Text>` - like `span` ([see here](https://reactnative.dev/docs/text))
- `<ActivityIndicator>` - A `spinner` ([see here](https://reactnative.dev/docs/activityindicator))
- `<Image>` as `img` ([see here](https://reactnative.dev/docs/image))
- `<Button>` as `button` ([see here](https://reactnative.dev/docs/button))
- `<TextInput>` as `input` ([see here](https://reactnative.dev/docs/textinput))

### Non button clickable components
- `ouchableOpacity` ([see here](https://reactnative.dev/docs/touchableopacity))
- `TouchableHighlight` ([see here](https://reactnative.dev/docs/touchablehighlight))
- `TouchableWithoutFeedback` ([see here](https://reactnative.dev/docs/touchablewithoutfeedback))

### Alert
- `Alert.alert()` ([see here](https://reactnative.dev/docs/alert))
- see that this does not work on web!

### List
- `<FlatList>` ([see here](https://reactnative.dev/docs/flatlist))
