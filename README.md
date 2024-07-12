

I used AsyncStorage because it persists data. It provides a simple key-value system that works well for persisting small amounts of data such as user preferences and settings. AsyncStorage also modularize data access by creating a dedicated storage utility.

How I Implemented My AsyncStorage:
Firstly, I installed the ' @react-native-async-storage/async-storage' package.(npm install @react-native-async-storage/async-storage)
Secondly, I created a storage utility module(storage.js) to encapsulate the data storage logic.
Thirdly, I integrated the storage utility functions within my React Native components to store and restore data.
And finally I used an external API to allow users to view and select what they want.

Screenshots

![IMG-20240712-WA0029](https://github.com/user-attachments/assets/f120b77b-f456-4583-baa1-553bbb566e50)


![IMG-20240712-WA0031](https://github.com/user-attachments/assets/44baadbb-32f0-4056-99d4-a1f2eb371e01)

![IMG-20240712-WA0028](https://github.com/user-attachments/assets/68aff77a-fc4d-4f29-9fa9-2689429cd852)

![IMG-20240712-WA0033](https://github.com/user-attachments/assets/e24e3e30-db00-4859-84d3-d6c5890a5f6a)
