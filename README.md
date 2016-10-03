#>>"STRINGS"

###There are lots of data types in Ruby. One of the most common is called a *string*.

A string is a group of any symbols that are surrounded by quotation marks like so:
`"Hello I am a string"`

You can use single or double quotes

`'I too am a string'`

And numbers

`"45298"`

Or symbols

`":)"`

Or EVERYTHING ALL AT ONCE

`"My first screen name was ladybugsroq2003! :) 8)"`

Really anything sandwiched between two quotation marks will be read as a string by Ruby.

Strings are great for storing data, communicating with your user, and really anything else you can think of when it comes to sending a message through code. Ruby has some awesome methods that we can use on our strings, which makes them an even more powerful data type.

## .upcase
Upcase does exactly what it says - it helps you `"YELL LOUDLY WITH YOUR STRINGS"`

Let's say you are given a string:

`"tgif I can't wait for the weekend!"`

Well that's well and good, but you think it would make a bit more sense in all caps.

Instead of rewriting the string completely, Ruby makes it easy:

	"tgif I can't wait for the weekend".upcase
		>> "TGIF I CAN'T WAIT FOR THE WEEKEND"

Appropriately loud, appropriately excited, and easily done.


## .downcase
Of course, if we have an upcase, we must have a downcase.

Let's say one of your friends Ben consistently types his comments in all caps, and you want to tone him down a bit.

`"OMG HEY GUYS WANT TO GET LUNCH TOMORROW PLZ?"`

A sweet request, but a little too intense.

	"OMG HEY GUYS WANT TO GET LUNCH TOMORROW PLZ?".downcase
		>> "omg hey guys want to get lunch tomorrow plz?"

Much better, and still just as sweet. Thanks Ben. Thanks Ruby.


## .reverse
Okay so now maybe your friend Timmy has sent you some text, and you realize it came through backwards --

`"!emit suoicerp ruoy lla etsaw ot sdrawkcab uoy ot siht gnipyT"`

What's the plan? Type everything out manually?

Ruby says no way.

	"!emit suoicerp ruoy lla etsaw ot sdrawkcab uoy ot siht gnipyT".reverse
		>> "Typing this to you backwards to waste all your precious time!"

You sure showed Timmy.

##Time to do it all
Alright so your friend Tina keeps sending you stuff like this:

`"?ooZ EHT oT OG oT TNaW UoY oD YaDNUS SIHT GNIoD UoY ERa TaHW YEH"`

You have a feeling her computer might be broken, and immediately run to your Ruby methods to try and decipher her message.

You quickly realize that the message is backwards, and you want to use the reverse method. You're also annoyed at the difference in capitalization, and want to use the downcase method to make things easier to read.

Of course, you could use one method at a time.

	"?ooZ EHT oT OG oT TNaW UoY oD YaDNUS SIHT GNIoD UoY ERa TaHW YEH".reverse
		>> "HEY WHaT aRE YoU DoING THIS SUNDaY Do YoU WaNT To GO To THE Zoo?"

	"HEY WHaT aRE YoU DoING THIS SUNDaY Do YoU WaNT To GO To THE Zoo?".downcase
		>> "hey what are you doing this sunday do you want to go to the zoo?"

This works. But your programmer senses are tingling, aren't they?

There must be an easier way....  and **there is**.

	"?ooZ EHT oT OG oT TNaW UoY oD YaDNUS SIHT GNIoD UoY ERa TaHW YEH".reverse.downcase
		>> "hey what are you doing this sunday do you want to go to the zoo?"

BOOM. One line of code and you have your answer.

Ruby allows you to chain methods together, making all of our dreams come true.		

Here are a few more string methods. Take a guess as to what they might do and try them out on your own!

	"string".capitalize

	"string".gsub('i', 'aaaaa')
	
	"string".replace("new string")
