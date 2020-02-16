# Resume

First Name: Mikhail
Last Name: Nikulenko

## Contact Info
email: nklnkm@yandex.ru

## Summary
I like the development. It is interesting to learn something new. But it is important that this can be put into practice and to do something useful, especially when the task is interesting. It's not hard for me to write code and be interested in the details. I am interested in inventing new things. I am also interested in art and beautiful things. I think that everything should be beautiful and comfortable in all areas of activity. And I think I can make something more comfortable, useful and beautiful.

## Skills
* JavaScript / HTML / CSS
* Delphi
* Git

## Code examples
javascript
```javascript
//set card (rectangular area on page) coordinates relative to cursor position
function setCardXY (eventObj) {
    let mousePageX = eventObj.pageX,//cursor in document (включая скролл)
        mousePageY = eventObj.pageY,
        mouseX = eventObj.clientX,//cursor in window
        mouseY = eventObj.clientY,
        clientWidthX = doc.documentElement.clientWidth,//window size
        clientHeightY = doc.documentElement.clientHeight,
        cardWidthX = parseInt(newCard.card.style.width, 10),
        cardHeightY = parseInt(newCard.card.style.height, 10);
    // draw card by X
    // to middle
    if ((mouseX + cardWidthX > clientWidthX) && (mouseX < cardWidthX)) {
        newCard.card.style.left = 5 + mousePageX + 'px';
    }
    // right
    else if (mouseX + cardWidthX <= clientWidthX) {
        newCard.card.style.left = 5 + mousePageX + 'px';
    }
    // left
    else if (mouseX + cardWidthX >= clientWidthX) {
        newCard.card.style.left = mousePageX - cardWidthX - 5 + 'px';//уточнить 9-ку
    };
    // draw card by Y
    // to middle
    if ((mouseY + cardHeightY > clientHeightY) && (mouseY < cardHeightY)) {
        newCard.card.style.top = 5 + mousePageY + 'px';//уточнить 9-ку
    }
    // bottom
    else if (mouseY + cardHeightY <= clientHeightY) {
        newCard.card.style.top = 5 + mousePageY + 'px';
    }    
    // top
    else if (mouseY + cardHeightY > clientHeightY) {
        newCard.card.style.top = mousePageY - cardHeightY - 5 + 'px';//уточнить 9-ку
    };
};
```

## Experience
Industrial control system engineer (SCADA development)

## Education
Saratov State University
Quality engineer

## English
Pre-Intermediate