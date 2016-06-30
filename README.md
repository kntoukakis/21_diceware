# 21_diceware
<h1>Generating secure and memorable passwords for bitcoin </h1>

<p>This service generates secure, memorable password suggestions for your apps or services, in exchange for bitcoin. </p>
<p> To use, run: </p>

<p align = "center">"21 buy url http://10.244.192.155:5000/make_password" </p>
<p>You will receive a json string of 5 (default) random generated words, in the form of a dictionary.</p>
<p align = "center"> {
    "password": [
        "alps",
        "push",
        "craft",
        "assam",
        "mc"
    ]
}
</p>
<p> To spesify a password length, add the desirable number of words as an integer at the end of the url, for example: </p>
<p align = "center"> "21 buy url http://10.244.192.155:5000/make_password/11" </p> 
<p> Maximum password length allowed is 16 words. </p>

