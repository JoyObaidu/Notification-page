# Frontend Mentor - Notifications page solution

This is a solution to the [Notifications page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/notifications-page-DqK5QAmKbC). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- Distinguish between "unread" and "read" notifications
- Select "Mark all as read" to toggle the visual state of the unread notifications and set the number of unread messages to zero
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![image](https://user-images.githubusercontent.com/106669781/231405487-cc4dc2a0-e2e8-452a-a4e5-d708d2f00ded.png)
![image](https://user-images.githubusercontent.com/106669781/231405530-13aeed12-70cb-40d1-8441-7a45da074788.png)



### Links

- Solution URL: (https://github.com/JoyObaidu/Notification-page)
- Live Site URL:(https://joyobaidu.github.io/Notification-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

 for (let i = 0; i < newNotif.length; i++) {
       newNotif[i].classList.remove("new");
        
       if (iconNotif[i].parentNode ===  message[i]) {
        message[i].removeChild(iconNotif[i]);
        numberNotif.innerHTML = parseInt(numberNotif.innerHTML) - 1;
       }
    }
});
### Continued development
Javscript loops

## Author

- Frontend Mentor - [@JoyObaidu](https://www.frontendmentor.io/profile/JoyObaidu)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)



