# React-Native-hooks

## useKeyboard
checking if keyboard is active
  ```javascript
  const keyboard = useKeyboard();
  const isActive = keyboard.keyboardShown;
```
  
## useBackHandler
checking if hardware back button pressed on a given page, and calling a callback function
eg.: asking for logout on HomeScreen with a modal

```javascript
  useBackHandler(() => {
    if (true) {
      setIsModalVisible(true);
      return true;
    }
  });
```
  
