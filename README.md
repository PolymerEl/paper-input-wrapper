[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/polymerEl/paper-input-wrapper)

# \<paper-input-wrapper\>

A simple wrapper for forms element that usually do not have `placeholders` or `labels` (e.g. \<paper-radio-group\>). 

Example Usage:

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-input-wrapper.html">
    <link rel="import" href="../paper-radio-group/paper-radio-group.html">
    <link rel="import" href="../paper-radio-button/paper-radio-button.html">
  	<next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
 <paper-input-wrapper label="this is the label" placeholder="my placeholder" value="{{data}}">
      <paper-radio-group class="select-content" selected="{{data}}">
        <paper-radio-button name="small">Small</paper-radio-button>
        <paper-radio-button name="medium">This is a long medium, just to check</paper-radio-button>
        <paper-radio-button name="large">Large</paper-radio-button>
      </paper-radio-group>
    </paper-input-wrapper>

```


