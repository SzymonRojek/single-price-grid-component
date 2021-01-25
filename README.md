
# Single Price Component

## 🎥 Preview site &rarr; [here](https://szymonrojek.github.io/single-price-grid-component/)

## **For this project I have used:**
* [x] HTML semantic elements;
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

Thanks to this challenge I read about ordered lists, especially in the context of the Safari browser and accessibility. When the list-style property is set to none (removing dots) **the VoiceOver** is not announcing unordered lists properly. For this reason, I can add **ARIA roles** list and listitem to restore the semantics, which helps to identify a list of items and return list in the VoiceOver. Here a problem arises because the validator throws a Warning: The list role is unnecessary for element ul/li. Definitely it is an intresting subject and I will find the best solution. 

## Setup

Clone this repo to your desktop and run this project locally.

The challenge comes from the website [Frontend Mentor](https://www.frontendmentor.io).