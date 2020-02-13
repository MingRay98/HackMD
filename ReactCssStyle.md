# React CSS Style

## Radim 套件

```js

':hover': {
  color: 'black',
},

'@media only screen and (max-width: 550px)': { //小於500最寬螢幕大小
  fontSize: '110%',
},

```

```jsx

<StyleRoot>  //這個要包起來才能用特規
  <div className="topContainer">
    <TopHeader />
    <div className="container">
      <div className="NavContainer">{this.getNavbar()}</div>
      {this.getRedirect()}
      {this.getPages()}
    </div>
  </div>
</StyleRoot>

```
