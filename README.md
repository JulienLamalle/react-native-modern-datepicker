# React Native Modern Datepicker 📆

A customizable calendar, time & month picker for React Native (including Persian Jalaali calendar & french locale). For more information, please visit [website](https://hosseinshabani.github.io/react-native-modern-datepicker)

This package is based on the work done by Hossein Shabani, so all the documentation is visible on his github page mentioned above.

The additions to this package are the support of the French language.

To use it you can do it as follows:

```js
import DatePicker from 'react-native-modern-datepicker-with-french';

<DatePicker
  locale="fr"
  onSelectedChange={date => {
    setStartDate(date);
  }}
  date={startDate}
  options={{
    defaultFont: 'MyriadPro-Regular',
    headerFont: 'MyriadPro-Bold',
    selectedTextColor: 'white',
    selectedBackgroundColor: '#001951',
    mainColor: '#001951',
    borderColor: '#001951',
  }}
  mode="calendar"
/>
```
