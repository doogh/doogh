# doogh
> 🥛An easy-to-use E2E test framework written in javascript targeting microservices systems

## Test Syntax
Write your scenarios easily. The assertions are usually done inside the wm (aka WorldModel) object.
```javascript
ts.test('Create a driver and passenger and go on a ride', aynsc (wm) => {
  const passenger = await wm.registerPassenger('firstName', 'lastName', 'email@address.com');
  const driver = await wm.registerDriver('firstName', 'lastName', 'email@address.com');
  const ride = await wm.goOnARide(passenger, driver, wm.sampleOrigin, wm.sampleDestination);
  // any other assetions on ride, passenger or driver objects
});
```

## Team

[![hoomanise](https://github.com/hoomanise.png?size=100)](https://github.com/hoomanise) | [![rajabzz](https://github.com/rajabzz.png?size=100)](https://github.com/rajabzz) | [![mrlotfi](https://github.com/mrlotfi.png?size=100)](https://github.com/mrlotfi)
---|---|---
[hoomanise](https://github.com/hoomanise) | [rajabzz](https://github.com/rajabzz) | [mrlotfi](https://github.com/mrlotfi)
