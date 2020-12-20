
# Single Price Component

## 🎥 Preview site [here](https://szymonrojek.github.io/single-price-grid-component/)

[Frontendmentor.io](https://www.frontendmentor.io/dashboard) challenge to build Single Price Component by using HTML and CSS:

* build out the project and get it looking as close to the design as [possible](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc) &#8592; check it out the link or the design folder;
* view the optimal layout for the site depending on device's screen size;

## **For this challenge I've used:**
- [x] HTML semantic elements:
- [x] Invisible content just for Screen Reader users;
- [x] BEM naming;
- [x] Pseudo-element for card overlay;
- [x] SASS;
- [x] Grid and Flex-Box;
- [x] Mobile First;
- [x] RWD;

- [x] Additional effects: 
- card overlay color (card three);
- button transform: move it up on hover and move down on click (active status) with changing background color;
- styled links in the footer: added a nice color to mark these links and light gray underline. Also light background color for links and blue border color on hover.


### Building project - relevant conclusions:

First time, I have used the grid and I was really enjoying to build this pricing component. Thanks to this challenge I read about accessibility in the ordered lists context. When property the list-style is set to none (removing dots) <span style="color:red">**the VoiceOver**</span> is not announcing unordered lists properly. For this reason I have started to use  <span style="color:blue">**ARIA roles**</span> list and listitem to restore the semantics, which helps to return list in the VoiceOver.


## Setup

Clone this repo to your desktop and run this project locally using npm to install all the dependencies.