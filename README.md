 Bible-CMS
===========
                                                                                                                         
**Golden Bible  CMS** [Open Source then — a lot of comments for programmers in source code; 512 **lines of code for file maximum**, unique identities from unique identity function, non-numeral identities]
one translation Bible {with install **any translation** from [eBible.org](http://ebible.org) [en-US - ASV, en-GB - KJV and etc.], install from txt - for SYN ru-RU translation}  
**Bible reading**: navigation on the Bible; copy link {kind of http://golden-bible.org/B:Gen:I:1}; Roman numerals for chapters; texted chapter number for opened chapter{kind of: first chapter, second chapter…}; random verse  
**Prayers**  
**add to favorites**: book, chapter or verse; show top readable and favorable things.  
**social things** for books, chapters and verses: Facebook, Google+, VK, twitter, tumblr, LJ… {All from YouTube social stuff?=}  
**Charity banners** or **links**: Red Cross banner and other charity organizations links — language depending {e.g. en-US, en-GB, ru-RU}.  
if defined in installation country has no charity info take random charity organization from base.
Registration: simple reg., + through socials;
                                                                                                              
                                                                                                              
Log In, Log Out;  
**Settings**: change: email, password, language  
It's neater to define user's language through `$_SERVER['HTTP_ACCEPT_LANGUAGE']`. Is it possible that it can be failed? In this case we can try ip to country function.  
`// pseudo `  
`if [SERVER['HTTP_ACCEPT_LANGUAGE'] != '']`  
  `set_language[SERVER['HTTP_ACCEPT_LANGUAGE']];`  
`else`  
  `set_language[get_language[ip_to_country[SERVER['REMOTE_ADDR'] ]]];`  
[, change translation to extra? — multi language countries]
IP to country. [when country don’t defined - switch to main translation]  
**mini-blog** posts with text, pictures or videos.
social notification about new post in blog? 
if it will be organization they can track their events there or anything else.]  
**mini-forum** private msgs  
Thank You Notes on bottom of the page.  
feedback;
                                                                                                              
Administration
--------------
user roles: moderation{timetable, prayers, holidays, org. info, contacts}, administration{all};  
charity {Red Cross and other organizations}, footer, Powered by Golden Bible CMS switching.  
visible languages;  
organization info and contacts.  
installation: themes, extra translations, change main translation  
change theme [e.g. Christmas, New Year and other Holidays]  
visibility of socials;  
switching: between roman and common numeral for chapters; import number texting module for language; switching Thank You Notes.  
reading timetable; Christian holidays; prayers editing;  
                                                                                                              
Installation page
-----------------
[first start]  
steps: language  
or add other language [CSV? dir: LTR or RTL], // installation should parse admin defined language file and make new COUNTRY_language.php file.  
choose visible languages for users;  
welcome page,  
theme, // preview  
main translation, // choose main Bible translation for page  
extra translations, // choose extra Bible translations  
set organization info // opt. e.i. can be switched off by admin to do not display it.  
set contacts info // opt.  
MySQL settings, pre installation page,  
// each translation should be different installation process from files GBF, XML or txt;  
installation.  
           
Features
--------
**Reading Without Numbers**  
If it will be not out of budget can you, please, add reading mode "Bible without numbers" and make it main mode. If people will wanna read with numbers they will can turn mode with numbers.
                                                                                                              
**Lite**  
Some people has a slow internet connection. And it will be good if they will have fast loading Bible.
Super Lite Bible with weight 50KB for one page and with inline CSS.
                                                                                                              
**Copyright**  
Bible CMS hosters can upload copyrighted Bibles in this way they should add copyright information and maybe Bible info.
Copyright information Bible CMS should show in the bottom of a chapter. Link to Bible info should be in under chapter and right justified.
                                                                                                              
**Charity Links**  
As you noticed the project has only one banner now - it's Red Cross.
It will be good to make other banners for charity organizations in style of Google Ads.
Because not a lot people will wanna go to page for charity organizations and every organization will have a chance to get a donating.
                                                                                                              
**Social Networking**  
All is said in subject. It's friends, private messages and other futures of that.
                                                                                                              
LICENSE
=======
This project has MIT license, which means you are free to take these sources and use it in any purpose or make you own Bible CMS.
                                                                                                              
                                                                                                              
