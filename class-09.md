# HTML & CSS

## Forms

You'll need a form, which lives inside a `<form>` element, if you wish to collect information from visitors.

You can use a variety of form controls to collect information from visitors to your website.

* Adding text
* Making choices
* submtting forms
* uploading files

## Lists & Tables

---

### Lists

There are three types of lists in HTML:

1- ordered list

It's used to number the list.

2- unordered list

It uses the bullets in the list.

3- definition list

it's used to define terminology.

---

### Tables

The table> element is used to add tables to a web page.

You indicate the start of each row using the opening tr> tag. (The tr stands for table row.)

Each cell of a table is represented using a td>element. (The td stands for table data.)

``` HTML
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

---

## JS

The browser uses events to indicate when something has happened (such as when a page has finished loading or a button has been clicked).

A JavaScript function can be called when an event happens on an element. Because this function has replied to the user, it feels interactive when it updates the web page in some way.

Example:

```JavaScript
<button onclick="displayDate()">The time is?</button>
```
