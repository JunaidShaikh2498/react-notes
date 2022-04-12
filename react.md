1) What is JSX?

=>JSX is a Javascript extension which enables us to write HTML code inside a Javascript file. Thus making it simpler to converge and embed the code into one single file.

2)What are features of react?

=> React is a JavaScript open source library which uses component based structure for the UI display.

a) React is becoming popular during the past few years because of it's easy learning curve. This is due to the base knowledge required to learn react i.e HTML,CSS,JavaScript.

b)Another feature is that react is faster and efficient compared to plain JavaScript. The reason for this is react uses a concept called virtual DOM.

c) So firstly DOM (Document object Model) is a tree like structure which contains all the HTML elements within it and <html> at it's root. Whenever a change occurs in the DOM the whole structure is reloaded/re-rendered which consumes unnecessery resources. To overcome this Virtual DOM was introduced in React. It is an exact copy of the Real DOM and there are 2 of them. Let's call it Fresh and Dirty Virtual DOM.
So whenever a change occurs on the page rather than reloadin the whole page the Dirty Virtual Dom changes its state. Then it is compared to the Fresh virtual DOM via Diffing algorithm which identifies the differences between nodes of the DOM. Then after changes are made the only part which changed is updated in the real DOM and rest is left unchanged. This whole process is known as reconciliation.

d) Also react has one way data binding. This means data flows in uni-direction i.e from Parent to child nodes and not vice-versa.