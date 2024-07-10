

I used AsyncStorage because it persists data. It provides a simple key-value system that works well for persisting small amounts of data such as user preferences and settings. AsyncStorage also modularize data access by creating a dedicated storage utility.

How I Implemented My AsyncStorage:
Firstly, I installed the ' @react-native-async-storage/async-storage' package.(npm install @react-native-async-storage/async-storage)
Secondly, I created a storage utility module(storage.js) to encapsulate the data storage logic.
Thirdly, I integrated the storage utility functions within my React Native components to store and restore data.
And finally I used an external API to allow users to view and select what they want.

Screenshots
