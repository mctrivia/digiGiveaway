# digiGiveaway
app to generate and populate large number of digibyte wallets

Currently only functional for single sided prints since back sides don't line up.

Costs 0.0001DGB/wallet.  Most of this money goes to miners to transfer funds.  If any is left over it goes in my dust wallet for future development.

Operation:
1) Download code onto your own computer.
2) disconnect from internet.  Code does not send private keys to me but best to be safe.
3) Run index.html and fill in the number of wallets you want to generate and how much is to go into it.
4) select wallet style you wish to use
5) generate wallets
6) print off wallets
7) after wallets have been printed and deemed visually acceptable press "destroy wallets" button
8) if you wish to make any more wallets with different designs go to step 4
9) copy data in large text box(skim through and verify I have not included private keys)
10) load fund.html
11) paste data into large text box
12) reconect to the internet
13) press generate
14) send payment to the address provided.
15) wait for confirmation window(note if anything goes wrong ctrl+shift+j will show debug window and private key of temp will be sent there so you can recover your money)
16) after about 30sec should show confirmation window.  All your wallets are now funded.


Warnings:
*At present there is a limit of 1000 wallets/fund cycle.  Will increase this to 1,000,000 in near future
*half thought bitcoin style is called that for a reason.  it is only a demo at this moment.
