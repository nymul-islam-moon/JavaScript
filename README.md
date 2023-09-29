<div align="center">

# **JavaScript**

# **Menu**
</div>

- ### [Template Literals](#template-literals-1)

- ### [Escape Sequence Characters](#escape-sequence-characters)


<h3 align="center" id="template-literals">Template Literals</h3>

#### First see the example 

```javascript
let friend_1 = 'Moon'
let friend_2 = 'Towkir'
let sentance = `${friend_1} can't be a friend of ${friend_2}`
console.log(sentance)
```


<p>Template literals use backtics of quots to display a string. Printing variable direct in string through template literals called string interpolation</p>

<h3 align="center" id="escape-sequence-characters">Escape Sequence Characters</h3>

```javascript
let sentence = `He said that 'You can\'t go out in the rain'` /** Use of \' */
let sentence_2 = `He said that "Both He\\She never went there"` /** Use of \\ */
let sentence_3 = `He said that "You can\t t go out in the rain"` /** Use of \t */
let sentence_4 = `He said that "You can\r t go out in the rain"` /** Use of \r */
let sentence_5 = `He said that "You can\b t go out in the rain"` /** Use of \b */
let sentence_6 = `He said that "You can\n t go out in the rain"` /** Use of \n */

console.log(sentence)
console.log(sentence_2)
console.log(sentence_3)
console.log(sentence_4)
console.log(sentence_5)
console.log(sentence_6)
```
using 