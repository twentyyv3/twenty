<img width="225" height="225" alt="images" src="https://github.com/user-attachments/assets/81daef50-3552-4877-bd59-5adedd25d825" />

##                                                                                                    ##
! Issues:

 Backround music is broken, some links may be damaged or blocked.
##                                                                                                    ##
+ Working:

All other features should function as expected
##                                                                                                    ##
**UPDATE LOG: added new games, and fixed search bar.**
##                                                                                                    ##
> Base Site:
https://twentyyv3.github.io/twenty/
##                                                                                                    ##
**Thanks for using twenty v14**
**this was completely developed by Riley/2K/Twenty**

##             ##

languages used
##             ##
html
##             ##
css
##             ##
javascript
##             ##







oh uh heres a free bookmarklet calc for any site
alert('use "c" on your keyboard to open calc and use "x" to fully close/delete script, this is beta and creds to twenty/riley');

function calcHandler(e){
    const k = e.key.toLowerCase();
    if(k === "c"){
        let eq = prompt("enter a math eq (multi = * | div = / | add = +| takeaway = -");
        if(eq){
            try{
                alert(eval(eq));
            }catch{
                alert("not math eq or wrong symbol D:");
            }
        }
    }
    if(k === "x"){
        document.removeEventListener("keydown", calcHandler);
        alert("script closed");
    }
}

document.addEventListener("keydown", calcHandler);

Put this in https://caiorss.github.io/bookmarklet-maker/
