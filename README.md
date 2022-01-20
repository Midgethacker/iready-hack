<p align="center"><img src="logo.jpg" alt="anti-iready-logo" width="43%" height="30%"/></p>

<h1 align="center">iReady Overload</h1>

## How to use/install

### Chrome Web Store
You can now hilariously download the extension on the chrome web store [here](https://chrome.google.com/webstore/detail/iready-overload/ddpalhmjafimblgfecimmdeafainoapp)

The installation is very simple, just click add to chrome and open i-ready. If your browser doesn't support the above or it's blocked for you, see the method below

### Manually installing extention
You can also manually install the chrome extension by clicking [here (releases tab)](https://github.com/cupiditys/iReady-Overload/releases) or [here (mirror latest download)](https://github.com/cupiditys/iReady-Overload/blob/main/chromeExtension.zip?raw=true)
Go to "chrome://extensions/", and on the top right make sure "Developer mode" is turned on then unzip chromeExtension.zip and drag the "iReady Overload" folder onto the page

### Bookmarklet

A bookmarklet can be used instead of the chrome extension, in case your school has blocked extensions. To do this:

1. Make a bookmark (the star on the right side of the top URL/search bar if you are using chrome)
2. Click on more at the bottom left corner
3. Delete everything in the URL box
4. Type javascript:
5. Paste in the following code
```fetch(`https://res.cloudinary.com/cupiditys/raw/upload/v${Math.floor(Math.random() * (999999 - 999) + 999)}/bookmarklet.js`).then((res) => res.text().then((t) => eval(t)))```
(this will auto-update)

Alternatively, you can use [this version](https://github.com/cupiditys/iReady-Overload/blob/main/bookmarklet.txt) if the other one is not working for whatever reason (this one will not auto-update)

## Disclaimers
<details>
<summary><b>Details</b></summary>
iReady is awful. It's the worst education tool anyone could ever use. I'm fed up with being forced to mindlessly watch the result of a greedy corporation that doesn't try in the SLIGHTEST to make their product enjoyable, or even acceptable. This repository is a collection of hacks and a chrome extension that ensures nobody has to suffer through iReady ever again. The current version has a **lesson & quiz skipper, a diagnostic hack, and a minutes hack**.
As of 1/14, this extension has ~26,000 users meaning 26,000 fewer people have to use iReady. Problem is, that barely makes a dent in iReady's 10,000,000+ students (0.0026%). If your school uses iReady, recommend this extension. They'll thank you. 
</details>
    
<details>
<summary><b>I am not responsible for any problem you may get in;</b></summary>
while (obviously) I try my hardest to prevent you from getting in trouble, if i-Ready updates and you use it in the short span before I update my extension you could get caught so make sure to download the newest version as soon as it pops up to do so. Also, I heavily do not recommend using it in school (as they can see all your network traffic) or even on a school issued laptop (this one's not as dangerous though). If want to be very safe, use your own personal computer at your own home.
</details>

## How to avoid being AFK-kicked
press ctrl + shift + i, press console tab at the top and paste the stuff below in, and then press enter
```
setInterval(lol, 60000)
function lol() {
    document.getElementById("btn-footer-MY_PROGRESS").click()
    document.getElementById("btn-footer-TO_DO").click()
}
```

## Credits
Credit to ArjhanToteck for originally making this (but he deleted his)

As shown below iReady's developer team has hilariously banned the text "iReady Overload" from their site so chances are they're reading this right now

![](https://cdn.discordapp.com/attachments/654687165837475840/905968971642179645/unknown.png)

They also added this :trollface:

![](https://cdn.discordapp.com/attachments/571058554216120322/911811161081671730/unknown.png)
