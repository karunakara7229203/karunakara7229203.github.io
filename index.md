## Welcome to Karunakar's Portfolio
You can use the [editor on GitHub](https://github.com/karunakara7229203/karunakara7229203.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/karunakara7229203/karunakara7229203.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<div class="button-group" id="redBlack">
  <h3>Button Group: Red-Black;<h3>
  <div class="button"> <span class="glyphicon glyphicon-headphones"></span> Music</div>
  <div class="button active"> <span class="glyphicon glyphicon-credit-card"></span> Shopping</div>
  <div class="button"> <span class="glyphicon glyphicon-cutlery"></span> Restaurants</div>
  <div class="button"> <span class="glyphicon glyphicon glyphicon-film"></span> Cinema</div>
</div>
 <script>
   $(document).ready(function() {
  buttonClick('#redBlack');
})

function buttonClick(string) {
  $(string).find(".button").click(function() {
    if (!$(this).hasClass('active')) {
      $(string + ' .active').removeClass('active');
      $(this).addClass('active');
    }
  })
}
   </script>
   
   <style>
  * {
  margin: 0;
  padding: 0;
  font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
  font-weight: 100;
}

.button-group {
  margin: 100px auto;
  width: 600px;
  margin-bottom: 30px;
  h3 {
    color: #999;
    text-align: center;
    font-size: 16px;
    margin-bottom: 10px;
  }
  &#redBlack .button {
    background: linear-gradient(135deg, #292929, #191919);
    border: none;
    width: 120px;
    height: 120px;
    padding: 20px;
    display: inline-block;
    margin: -4px;
    color: #F2070B;
    font-size: 14px;
    text-align: left;
    text-shadow: 0 0 10px rgba(181, 26, 30, 0.4);
    box-shadow: 0px 10px 30px rgba(28, 28, 28, 0.9);
    span {
      text-align: center;
      margin: 20px 0 20px 0;
      display: block;
      color: #fff;
      font-size: 32px;
      text-shadow: none;
    }
    &:hover {
      background: linear-gradient(-45deg, #292929, #191919);
    }
    &.active {
      background: #B51A1E;
      color: #fff;
      box-shadow: inset 0px 0px 30px rgba(28, 28, 28, 0.9);
    }
  }  
}
  </style>
