### Team Demo

##### A Presentation going over proposed UI/UX changes to Unibit applications. 

---?image=/assets/image/Light-Grey-Background-Tumblr-8-1024x640.jpg&opacity=100

### Test Background

slide info

---

### Encryption App

![alt](/assets/image/demo/cryptit-main.jpg)

- Current home screen UI design |
- Current website --> | https://securedoc.io |

---

### Encryption App Modified

![alt](assets/image/encryption-app-mod.jpg)

- Proposed main screen changes --> http://google.doc.whatever |
- Future website --> https://encryption.app |

---

### Voting App

![alt](/assets/image/demo/voteapp-main.png)

- Current main screen |
- Current website --> http://voteapp.gq

---

### Voting App Modified

![alt]()

- Proposed main screen changes |
- Future website --> https://vote.app

---

### UBIT Web Wallet Design

![alt](/assets/image/demo/ubit-main.png)

- Current web wallet design |
- Current website --> http://ubit.chickenkiller.com

---

### UBIT Web Wallet Modified

![alt]()

- Proposed web wallet changes 
- Future website | --> https://wallet.unibit.app

---

### UMW App

![alt](/assets/image/demo/umw-main.png)

- Current home screen UI design 
- Current website --> http://unibit.rundis.com 

---

### UMW App Modified

![alt](assets/image/encryption-app-mod.jpg)

- Proposed main screen changes --> http://google.doc.whatever 
- Future website --> https://encryption.app 

---

### Scout Browser App

![alt](/assets/image/demo/scoutbrowser-main.png)

- Current home screen UI design |
- Current website --> http://scout.click |

---

### Scout Browser App Modified

![alt](assets/image/encryption-app-mod.jpg)

- Proposed main screen changes --> http://google.doc.whatever |

---

### Suggested Changes

- Matching Color Scheme Across All Products/Services? |
- Open Source? Proprietary? |
- Custom 3D/Animated Styling |
- Custom Logo, TOC, and Footnotes |

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---

### Suggestions & Help

- [Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Polling](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Introducing](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [Revising](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom Branches](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting) [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents) [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

### Go Pro!

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details hidden here.</a>
</div>
<div class="right">
    <ul>
        <li>Private Repos</li>
        <li>Private URLs</li>
        <li>Password-Protection</li>
        <li>Image Opacity</li>
        <li>SVG Image Support</li>
    </ul>
</div>

---

### Questions?

<br>

@fa[twitter gp-contact](@us)

@fa[github gp-contact](us)

@fa[medium gp-contact](@us)

---?image=assets/image/gitpitch-audience.jpg&opacity=100

@title[Download this Template!]

### <span class="white">Get your tasks started!</span>
### [Download @fa[external-link gp-download]](https://gitpitch.com/template/download/white)

