```javascript

collection1 = getCollection1();
collection2 = getCollection2();
collection3 = getCollection3();

process(somethingInTheWay, target);
process(somethingInTheWay, target);
process(somethingInTheWay, target);

```

`yiw` - yank the word into the yank register
`jww` - move down 1 line to 'somethingInTheWay'
`ciw<C-r>0` - insert the text from the yank register

Duplicate the `<tr>` tag content

```html
<table>

  <tr>
    <td>keystrokes</td>
    <td>buffer contents</td>
  </tr>

</table>
```

`yap` - yanks the paragraph
`5j` - move down 5 lines
`gP` - insert above
