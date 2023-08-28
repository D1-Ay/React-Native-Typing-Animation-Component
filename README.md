
# React Native Typing Animation Component

A reusable React Native component that simulates a typing animation, displaying text character by character.


## Features

- Smooth and customizable typing animation.
- Control animation speed and text content.
- Easily integrate it into your React Native projects.


## Installation

Install the component with npm

```bash
  npm i d1_ay-typinganimation
```
    
## Usage/Examples

```javascript
iimport React from 'react';
import { StyleSheet, View } from 'react-native';
import TypingAnimation from 'd1_ay-typinganimation/TypingAnimation';

const App = () => {
  return (
    <View style={styles.container}>
      <TypingAnimation
        speed={20}
        style={{ fontSize: 20, fontFamily: 'monospace', color: 'black' }}
        message={'Hello, world! This is a typing animation.'}
      />
    </View>
  );
};

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});

export default App;

```


## props
-`style` (Object): Custom styles to be applied to the text.

-`message` (string): The message to be displayed in the typing animation.

-`speed` (number, optional): The speed of the typing animation in milliseconds per character.
