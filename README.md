# xkcdpwgen

## Importance of passwords

Based off the popular xkcd sketch, on how to not make passwords in the modern age. 

The original, and most common way to make secure passwords these days involves:
	1) Really fucking unreadable passwords
	2) Making them longer to make them even more unreadable 
And this is considered 'safe' and effective but is also maladaptive to what we are really trying to solve 

It's confusing, unreadable and is actually not as secure as we thought.

Consider this:
	S = L * log_2N
This is the formula to determine the strength (in bits) of a specific password,
Where the L is the length and N is symbols and numbers.

This shows how important the length of the password is more than anything else,
with this knowledge we can develop passwords that we can memorize and are strong
against hash cracking.

## How to use

This tool is very easy to use, and you have two general options.

1) Install it to your /usr/bin to run it with the term xkcdpwgen 
2) Install it to any directory and run it with ./xkcdpwgen 

Thats it!

You can add parameters such as 

-n (Numbers) 
-s (Symbols)
-w (Words)
-c (Caps)

All these symbols add to the strength of the password to make it even stronger
although it may become less readable.

To store your password to a textfile, pipe it using > <name_of_txt_file>


