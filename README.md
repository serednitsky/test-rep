```javascript
const makeItFunny = (str, position) => {
  let i = 0;
  let result = '';

  while (i < str.length) {
    if ((i + 1) % position === 0) {
      result = `${result}${str[i].toUpperCase()}`;
    } else {
    result = `${result}${str[i]}`; 
    }
    
    i++;
  }
  return result;
};
````
