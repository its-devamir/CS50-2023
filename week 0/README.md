# Unary
base-1
we only access a digit to represent all other digits.

# Binary Digit (bit)
base-2
0 and 1. As a turned on light bulb represents 1 and a turned off one represents 0, computers have millions switches (transistors) that can be 1 or 0 (electricity is there or not)

### But how to count more than 1 ?
let say we have 💡💡💡 thess three light bulbs. Always remember we are gonna get the maximum outcome (numbers) of these three compilation. These three represent 4 - 2 - 1 regardingly. If we add one more (💡💡💡💡) it will be 8 - 4 - 2 - 1. At first we could count up to 7, now we can count up to 15. 
Do not forget the digit (0): Meaning that first we could make 8 and then 16 digits using only  light bulbs ( zeros and ones )

Generally = ... | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup>

### 8 bit compueter
it counts from 00000000 to 11111111. Meaning 0 t0 255 in human language (decimal)
So bits are not tat usefull. We use bytes more often (**1 byte = 8bits**)

kilo-bytes = thousands of bytes
mega-bytes = millions of bytes
giga-bytes = bilions of bytes
....

# Decimal
base-10
for example one hundred twenty three, is a pattern of three digits = 123

----------

# Letters
Each letter is being represented by a number. For example
A = 65  (ex:01000001)
B = 66
C = 67
. . . . .

#### So what if we wanna show the number itself, and not a letter?
Turns out there's a whole system that maps numbers to letters. It is Called ASCII (American Standard Code for Information Interchange)
 ![ASCII Chart](https://www.asciitable.com/asciifull.gif)
 ![ASCII Chart exntended](https://www.asciitable.com/extend.gif)

So what about the question?
you can see that the numbers themselves are included in ASCII. Forexample
0 = 48
1 = 49
2 = 50
. . . . 

# Colors
They also are a compilation we all agreed on

# Even More (Emojies, Other Languages and ...)
8 bit system lets ASCII to include only 256 characters.Now what???
Simple :) add another digit. We go up to 32bits, 64bits and ... nowadays.

so the solution to ASCII was UNICODE . (the same but much much much much ... more complete)

# Unicode
32bits = means 4 billions possible chracter. Room for having fun !!!
like number 4036991106 represents 😂
nowadays we have different skin tones too. lol

#### the point is each skin tone does not take another number
Unicode decided that the first bytes represent the emoji itself (default yellow version)
but if it is followed by a certain pattern of bits that represent the skin tones, the OS will change the skin tone

#### nowadays we have combined emojies too. like 👩‍❤️‍👨(combination of three)

#### why is the output different? Android VS IOS VS Windows VS ...
we know that emojies are not images, the are characters. So instead of saying that different companies use different images lets say they use different fonts

----------

# RGB, Images and Videos
every pixel on your device is number too. like 72 73 33: as the amount of red, green and blue regardingly.
images are pixels alongside each other
videos are sequences of images

# Musics
sound is some frequency. how are they implemented in our decive? their duration, volume.
it is a sequence of music note, patterns and ... 
but there are different way of representing. Like mp3, AAC and ...
