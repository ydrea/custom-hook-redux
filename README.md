# custom-hook-redux
a simple toggle of an RTK slice boolean value

to use:
```
  const [BAR, { setToggleRedux }] = useBoolRedux(false);
  
      <Button className="button" onClick={setToggleRedux}>
        setToggleRedux
      </Button>
      {BAR.toString()}
  ```
  inspired by Robin Wieruch's https://www.robinwieruch.de/react-custom-hook/
  
