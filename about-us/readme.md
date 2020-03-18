# About Us

GitDocs was built by the good folks over here at [Timber](https://timber.io). 
You should check us out.
Hi



# test
this is a test! i dunno what will i have as a result, but let s see


Alt-H1
======

hello, guys how are you! 
i hope you re fine, and take the l3ibat rah corona kador!

Alt-H1
======


```javascript

C_TEXT($1;$attribut)
C_TEXT($0;$value)

ARRAY OBJECT($_adresses;0)
C_OBJECT($address)
C_OBJECT($detail)

$attribut:=$1

OB GET ARRAY([Member]address;"address";$_adresses)
If (Size of array($_adresses)>0)
	
	$address:=$_adresses{1}
	$detail:=OB Get($address;"detail";Is object)
	$value:=OB Get($detail;$attribut;Is text)
Else 
	$value:=""
End if 

$0:=$value
```