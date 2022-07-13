# day-03
For the given JSON iterate over all for loops:

JSON iterate  FOR LOOP:
var json = [{
    "id" : "1", 
    "msg"   : "ABC",
    "tid" : "2013-05-05 23:35",
    "fromWho": "hello1@email.com"
  },
  {
    "id" : "2", 
    "msg"   : "XYZ",
    "tid" : "2013-05-05 23:45",
    "fromWho": "hello2@email.com"
  }];

  for(var i = 0; i < json.length; i++) {
    var obj = json[i];

    console.log(obj.id, obj.msg, obj.fromWho);
  }
  

JSON iterate  FOR IN LOOP:
var person={
     "first_name":"johnny",
      "last_name": "johnson",
    "phone":"703-3424-1111"
};
for (var property in person) {
      console.log(property,":",person[property]);
}


Create your own resume data in JSON format
var Details={
     "NAME":"MOGANA",
     "E-MAIL ID": "monisha26596@gmail.com",
     "MOBILE NUMBER":"9952835408", 
     "QUALIFICATION":"B.Tech(ECE)",
     "PASSED OUT":"2017",
     "PERCENTAGE":"83%"
   };
for (var property in Details) {
      console.log(property,":",Details[property]);
}


Different between screen, window and document in Javascript:

Window:
The JavaScript window object sits at the top of the JavaScript Object hierarchy and represents the browser window. The window object is supported by all browsers. All global JavaScript objects , functions, and variables automatically become members of the window object. The window is the first thing that gets loaded into the browser . The window object represents the current browsing context . It holds things like window.location, window.history, window.screen, window.status, or the window.document . Each browser tab has its own top-level window object.

Document:
The Document interface represents any web page loaded in the browser and serves as an entry point into the web page's content, which is the DOM tree. When an HTML document is loaded into a web browser , it becomes a document object. It is the root node of the HTML document. The document actually gets loaded inside the window object and has properties available to it like title, URL, cookie, etc. HTML documents, served with the "text/html" content type, also implement the HTMLDocument interface, whereas XML and SVG documents implement the XMLDocument interface.

Screen:
Screen is a small information object about physical screen dimensions . It can be used to display screen width, height, colorDepth, pixelDepth etc. It is not mandatory to write window prefix with screen object. It can be written without window prefix.
Properties:
screen.width
screen.height
screen.availWidth
screen.availHeight
screen.colorDepth
screen.pixelDepth
