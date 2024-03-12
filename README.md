# prep-notes

Single sign-on (SSO) is the process by which a user can log in to multiple applications using a single set of credentials. 

Local Storage: This read-only interface property provides access to the document’s local storage object; the stored data is stored across browser sessions. 
Similar to sessionStorage, except that sessionStorage data gets cleared when the page session ends—that is, when the page is closed. 
It is cleared when the last “private” tab of a browser is closed (localStorage data for a document loaded in a private browsing or incognito session).

Session Storage objects can be accessed using the sessionStorage read-only property. The difference between sessionStorage and localStorage is that localStorage data does not expire, whereas sessionStorage data is cleared when the page session ends.

A unique page session gets created once a document is loaded in a browser tab. Page sessions are valid for only one tab at a time. Pages are only saved for the amount of time that the tab or the browser is open; 
they do not persist after the page reloads and restores. A new session is created each time a tab or window is opened; this is different from session cookies.
Each tab/window that is opened with the same URL creates its own sessionStorage.When you duplicate a tab, the sessionStorage from the original tab is copied to the duplicated tab.
Closing a window/tab ends the session and clears sessionStorage objects.

Cookie: The term “cookie” refers to just the textual information about a website. In order to recognize you and show you results according to your preferences, this website saves some information in your local system when you visit a particular website.
Since a server receives many requests every second, storing every user’s information on a server doesn’t seem logical and obvious. The same information may not be needed again if you don’t return. Therefore, a cookie is sent and stored on your local machine to uniquely identify you. You will receive a response from the same server the next time you hit it since it recognizes you.


Vectorizing your solution makes it run 300 times faster than normal code (ML deep learning), the RULE TO REMEMBER is whenever possible, avoid using explicit for loops. Whenever tempted to use for loop, just go and check if theres a bulit in thing in numpy to replace it. 
