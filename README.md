# react-native-loader
A collection of animated spinners for react native using ReactART.

![Demo](http://f.cl.ly/items/2W0s3L1s3H2W1i2l3q14/react-native-loader.gif)

# Usage
## Installation
Install it via npm:

```
npm i -S github:ajaykumar97/react-native-loader#master
```
or
```
yarn add github:ajaykumar97/react-native-loader#master
```

### Android
For Android, it works out of the box.

### iOS
Install ``@react-native-community/art`` from [@react-native-community/art](https://github.com/react-native-community/art)

## How to use
```jsx
import { Bubbles, DoubleBounce, Bars, Pulse } from 'react-native-loader';

// ...
<View>
  <Bubbles size={10} color="#FFF" />
  <Bars size={10} color="#FDAAFF" />
  <Pulse size={10} color="#52AB42" />
  <DoubleBounce size={10} color="#1CAFF6" />
</View>

```
