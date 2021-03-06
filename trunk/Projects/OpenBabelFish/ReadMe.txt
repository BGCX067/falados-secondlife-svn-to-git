#summary Setup and Operation Instructions
= Introduction =
So you've downloaded Open Babel Fish and you want to know how to use it.
This step by step guide will allow you to get this working as fast as possible.

==Things You'll Need==

  # Online Webspace with PHP
  # The PHP Module 'libcurl' must be installed or url fopen must be enabled. (You may pick which one in the php file)
  # A prim
  # A Notecard named URL
  # A little patience

==Step by Step Setup==

===1===
The first thing you must do is get online web space. Now this isn't as difficult as it sounds. A lot of places have some free limited web space, but you need to be picky about which one you get. The on I used is [http://www.x10hosting.com/] and they've been very good so far.  You must apply for their Intermediate PHP version, which they usually accepts without question. This version will give you access to the required php functions that are otherwise restricted.

A list of other sites can be found here which have a lot of specifications:
    [http://www.free-webhosts.com/free-php-webhosting.php]

===2===
Simply upload the babel.php,lang-sl.txt, and lang-tl.txt to your site (In the same directory)
Remember the address of that file. It may be something like http://yourhost.com/your_user_name/babel.php, but this will vary from host to host.

===3===
Create a prim (or object) and attach it to yourself.  

===4===
Edit the URL Notecard, put the location of your babel.php file as the first line.

===5===
Put the URL Notecard into the prim

===6===
A dialog will come up with 'What language?' in various languages.  Pick your native language. You can press the >> and << buttons to go back and forth if your language isn't listed on the page displayed.

===7===
You should get a message that lists all the chat commands. Read that and get acquainted.

===8===
Enjoy and expand your horizons!

==Commands==
Depending on what channel you've selected, (Default is 55) here are the commands:

/55 autotrans <name>
    * This command will attempt to automatically translate someone using Google Translate's Auto-Detection option.

/55 translate <name>
    * This command will send a dialog to the user you have specified under <name>.  Keep them within chat range as their response must be heard by the Babel Fish script.  If the successfully respond before the timeout period, they will be added to your list of translations under the language they have picked. The <name> is first partial match.

/55 remove <name>
    * this command removes <name> from the translations list.  <name> must be the full name and is case-sensitive.  Try doing a /55 list and copy/pasting the name if you are having trouble.
    
/55 remove all
    * this command removes all translations from the list. Essentially resetting the Babel Fish to the point after you have picked your native language.

/55 speak
    * Upon using this command, you will be asked what language you wish to speak.  After you've selected your language, and chats that you do on channel 0 will be echo'ed by the babel fish (under your name) in the language you have chosen.

/55 list
    * Displays the list of all people who will be translated and the language pair associated with them.

/55 help
    * Displays the list of commands you may use and a brief description to remind you how they work.

/55 reset
    * Resets the Open Babel Fish core script.