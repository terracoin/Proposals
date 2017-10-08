How to put in a Proposal

1. Useful console commands

getgovernanceinfo - This shows when the next superblock will be produced.
gobject list - This shows the proposals currently available for voting.
gobject vote-many HASH funding yes (or no).

2. How it works

This is a very complicated process and at a future date we will have a proposal website where most of this will be done for you.

To put in a proposal it costs 10 TRC so before you put in the proposal you will want to make sure that you have a general idea if the proposal will pass or not.

Also keep in mind that there is a limited amount of budgetary funds available.

21,600 TRC is available for proposals approximately every 30 days.  If there are more requested TRC then there is available TRC the pay outs are done in order of highest number of yes votes.

This means that you want to get your proposals in early in the budget cycle and you want to make sure you have a good chance of winning.

3. Tools needed

You will need a Ascii Text to Hexadecimal converter that can remove "padding" I recommend this one: http://www.binaryhexconverter.com/ascii-text-to-hex-converter

Uncheck the padding option

You will also need to convert current and future times into a Epoch Unix Time Stamp.  Here is the site I recommend: https://www.unixtimestamp.com/

4. How to do it

Now is when it gets complicated.

Each proposal needs this info:

[["proposal",{"end_epoch":"1539000000","name":"Terracoin Team Pay","payment_address":"1LKRZGiYSM74PtPCHLd3yRMDFa6qeMWxxh","payment_amount":"6480","start_epoch":"1507488816","type":1,"url":"https://github.com/terracoin/proposals/issues/2"}]]

This looks like a big pile of garbage so I will break it down.

"proposal" just means that you are putting in a proposal so that always needs to be there.

"end_epoch" is the approximate time when the proposal ends.  So if you want the proposal to last a year you will need to use the Unix Time Stamp page to figure that out.

"name" a name for the proposal

"payment_address" this is your TRC address where you will receive payment

“payment_amount” is the amount you will get paid per 30 day period

“start_epoch” is the Unix Time Stamp of when you want the proposal to start.  Depending how far into the proposal month you are you might want it to start the next month.

“type” should always be 1.

“url” This is the url of your proposal.  It can be any website, but it is recommended that people use the issues tab here on Github.

Once you have filled out all of those areas your proposal should look