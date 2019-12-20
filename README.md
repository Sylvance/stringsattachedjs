# Stringsattachedjs
Attach, detach strings

## Installation
- Run;
`npm install stringsattachedjs`

## Usage
To attach strings;
```
require Str

str1 = 'first string'
str2 = 'second string'

str3 = Str.attach(str1, str2)
console.log(str3)
#=>  'first string second string'
```
To attach an array of strings;
```
require Str

str1 = 'first string'
str2 = 'second string'
str3 = 'third string'

arr_str = [str1, str2, str3]

str4 = Str.attach(arr_str)
console.log(str4)
#=>  'first string second string third string'
```

## Contributing
To contribute:
- Fork this branch.
- Make changes on your fork.
- Make a pull request back to this repo with the changes.

## Author
Sylvance Mbaka

