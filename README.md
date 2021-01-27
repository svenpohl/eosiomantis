# eosiomantis 
Wordpress EOSIO-Plugin
version: 0.01 (first draft)


Current live-demo:
https://xuso.de/demo/


# features / shortcodes for wordpress

* Anchor-Wallet login []
* Show EOS-balance of logged in account/accountname
* Simple donation area (configurable amounts)

* Example content for a donation page*
```
[eos_anchor] 
[eos_accountname greeting='Hello'] 
[eos_balance contract='eosio.token' token='EOS' ] 
 
 
To support me please donate via EOS! 
[eos_donator contract='eosio.token' token='EOS' receiver='fivenovember' amountlist='0.0002;0.0003;0.1000;1.0000' amount='0.0002' buttontext='Donate' memo='Thank you!!!'] 

[eos_donator_thankyou_content_begin]
Thank you sooo much for your donation!!! 🌻


[eos_donator_thankyou_content_end]
```


# please note
Don't forget to enable the checkbox for:
"[x] include EOSIO resources (css/javascript) for this page"
on each page. EOSIO includes are only included if needed on the given wordpress page or post.




*...to be continued*
