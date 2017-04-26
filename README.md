# pf-elements
A Polymer 2.0 based collection of reusable web components 

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

## Demo

[Demo and API docs ↗](https://www.webcomponents.org/element/PFElements/pf-pageindicator/demo/demo/index.html)

_[Demo and API docs](https://www.webcomponents.org/element/PFElements/pf-pageindicator/demo/demo/index.html)_

# PF Page Indicator.

A Polymer 2.0 based custom elements that can be used to indicate the current page in a stack of pages. 

PF Elements is a collection that contains all elements listed below.


| Element Name | Latest Version (Bower) | Npm version  | Build Status |
|--------------|------------------------|--------------|--------------|
| [pf-pageindicator](https://github.com/PFElements/pf-pageindicator) | [![GitHub version](https://badge.fury.io/gh/PFElements%2Fpf-pageindicator.svg)](https://badge.fury.io/gh/PFElements%2Fpf-pageindicator) | [![npm version](https://badge.fury.io/js/pf-pageindicator.svg)](https://www.npmjs.com/package/pf-pageindicator) |[![Build Status](https://travis-ci.org/PFElements/pf-pageindicator.svg?branch=master)](https://travis-ci.org/PFElements/pf-pageindicator) | 


## Example

`<pf-pageindicator></pf-pageindicator>` can be passed the number of pages (or dots) that you want to display, additionaly you can pass the style of the transition as well.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="pf-pageindicator.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<pf-pageindicator dotstyle="dotstyle-smalldotstroke" totaldots="5"></pf-pageindicator>
```
```html
<pf-pageindicator dotstyle="dotstyle-number" totaldots="5"></pf-pageindicator>
```
## Learn more

See the list of elements, demos, and documentation by browsing this collection on webcomponents.org:

### [Take me to webcomponents.org ›](https://www.webcomponents.org/element/PFElements/pf-pageindicator)

---

## Contributing

Comments, questions, suggestions, issues, and pull requests are all welcome.

### Get in touch with the team

Joing us at [![Join the chat at https://gitter.im/pf-elements/Lobby](https://badges.gitter.im/pf-elements/Lobby.svg)](https://gitter.im/pf-elements/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- [Twitter](<a href="https://twitter.com/polymerio" class="twitter-follow-button" data-show-count="false">Follow @polymerio</a>)
- [Facebook] (https://www.facebook.com/polymerjs)
- [Google+] (https://plus.google.com/116168214823506639166) 
- [YouTube] (https://www.youtube.com/channel/UCDKqvDyAn_QTBvCPvrZKTkw) 


### Some ways to help:

- **Test the elements and provide feedback**: We would love to hear your feedback on anything related to the elements, like features, API and design. The best way to start is by trying them out. And to get a quick response, either drop a question/comment on the chat or open an issue in GitHub.
- **Report bugs**: File issues for the elements in their respective GitHub projects.
- **Send pull requests**: If you want to contribute code, check out the development instructions below.

We encourage you to read the [contribution instructions by GitHub](https://guides.github.com/activities/contributing-to-open-source/#contributing) also.

## License

MIT License

## Credits
Insparation for this component came from multiple sources.  
https://github.com/codrops/DotNavigationStyles is one of the insperation
