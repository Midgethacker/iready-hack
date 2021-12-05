# iReady-Overload
iReady is awful. It's the worst education tool anyone could ever use. I'm fed up with being forced to mindlessly watch the result of a greedy corporation that doesn't try in the SLIGHTEST to make their product enjoyable, or even acceptable. This repository is a collection of hacks and a chrome extension that ensures nobody has to suffer through iReady ever again. The current version has a lesson, quiz skipper, and a minutes hack. 

As of 12/4, github says this repo has ~14,000 downloads meaning 14,000 less people having to use iReady. Problem is, that barely makes a dent in iReady's 10,000,000+ students (0.0014%). If your school uses iReady, recommend this extension. They'll thank you. 

# How to use/install
Download the chrome extension by clicking [here](https://github.com/cupiditys/iReady-Overload/blob/main/chromeExtension.zip?raw=true)

Go to "chrome://extensions/", and on the top right make sure "Developer mode" is turned on (if your school blocks this, see the bookmarklet below)
then unzip chromeExtension.zip and drag the "iReady Overload" folder onto the page and ur good

# Bookmarklet

A bookmarklet can be used instead of the chrome extension, incase your school has blocked extentions. To do this:

1. Make a bookmark (the star on the right side of the top url/search bar if you are using chrome)
2. Click on more at the bottom left corner
3. Delete everything in the url box
4. Type javascript:
5. Paste in the following code
```fetch(atob('aHR0cHM6Ly9yZXMuY2xvdWRpbmFyeS5jb20vY3VwaWRpdHlzL3Jhdy91cGxvYWQvdjE2MzgzNDExMjEvYm9va21hcmtsZXQuanM=')).then((res) => res.text().then((t) => eval(t)))```
(this will auto-update)

Alternatively, you can use [this version](https://github.com/cupiditys/iReady-Overload/blob/main/bookmarklet.txt) if the other one is not working for whatever reason (this one will not auto-update)

# How to avoid being AFK-kicked
press ctrl + shift + i, press console tab at top and paste the stuff below in and obviously press enter
```
setInterval(lol, 60000)
function lol() {
    document.getElementById("btn-footer-MY_PROGRESS").click()
    document.getElementById("btn-footer-TO_DO").click()
}
```

# Extra
credit to ArjhanToteck for originally making this (but he deleted his)

as shown below iReady's developer team has hilariously banned the text "iReady Overload" from their site so chances are they're reading this right now

![](https://cdn.discordapp.com/attachments/654687165837475840/905968971642179645/unknown.png)

they also added this :trollface:

![](https://cdn.discordapp.com/attachments/571058554216120322/911811161081671730/unknown.png)
