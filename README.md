
# Single Price Component

## 🎥 Preview site [here](https://szymonrojek.github.io/single-price-grid-component/)

[Frontendmentor.io](https://www.frontendmentor.io/dashboard) challenge to build Single Price Component by using HTML and CSS:

* build out the project and get it looking as close to the design as [possible](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc) &#8592; check it out the link or the design folder;
* view the optimal layout for the site depending on device's screen size;

## **For this challenge I've used:**
* [x] HTML semantic elements:
* [x] Invisible content just for Screen Reader users;
* [x] BEM naming;
* [x] Pseudo-element for card overlay;
* [x] SASS;
* [x] Grid and Flex-Box;
* [x] Mobile First;
* [x] RWD;

* [x] Additional effects: 
- card overlay color (third card);
- button transform: move it up on hover and move down on click (active status) with changing background color;
- styled links in the footer: added a nice color to mark these links and light gray underline, light background color for links and blue border color on hover.


### Building project - relevant conclusions:

Thanks to this challenge I read about ordered lists, especially in the context of the Safari browser and accessibility. When the list-style property is set to none (removing dots) **the VoiceOver** is not announcing unordered lists properly. For this reason, I've added **ARIA roles** list and listitem to restore the semantics, which helps to identify a list of items and return list in the VoiceOver.


## Setup

Clone this repo to your desktop and run this project locally using npm to install all the dependencies.