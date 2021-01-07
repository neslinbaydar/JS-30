# Geolocation Project

The aim of this project is using **Geolocation API** we can access location information in a couple of different ways:

🎯Geolocation.getCurrentPosition()
🎯Geolocation.watchPosition()

**We can define like this:**

const watchID = navigator.geolocation.watchPosition((position) => {
  doSomething(position.coords.latitude, position.coords.longitude);
});

![1](https://user-images.githubusercontent.com/37474673/103811123-7a648f00-506d-11eb-9617-93ff820e8196.png)

![Adsız1](https://user-images.githubusercontent.com/37474673/103811267-b5ff5900-506d-11eb-9fec-3590c7452f7b.png)


PS: For more information please click below link.

**[📌](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API/Using_the_Geolocation_API)**
