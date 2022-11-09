# Class 13 Notes

1. Why would a developer use local storage for a web application?
Local storage could be used so that the local storage can cache certain items. It can help the user in turn by not having the need to have to load all of the same stuff they already did. It allows the developer to store the state of their interface in a location such as your local storage.

2. What information should not be stored in local storage?
Sensitive information should not be stored in local storage as it can easily be accessed through cookies.

3. Local storage can store what type of data? How would you convert it to that type before storing?
It can only store strings. You can work around it by using either the JSON.stringify() or JSON.parse(methods).