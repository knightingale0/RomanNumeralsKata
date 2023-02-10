The OriginalCode file is my first pass of the full code. It works for values of 1-9999, but gets fussy about the thousands place if it's empty.
  This version also breaks down what each value was for each place.
  It is redundant, as I discovered when I tried shortening it the first time in the document titled SecondTry
  
SecondTry is the same basic function as the original, but I cut the redundant part that runs for different lengths of input numbers
  I also cut the section calculating the thousands place drastically, as the Kata document does say it's only really needed up to 3000
  I combined the first two lines, now that length was an unneeded variable, and dropped the part at the end that breaks down the input number
  
ShorterCode is a verison that I had to do more googling for; I knew that the code was redundant between each place value
  I wanted to make a loop that would play through the code for each place value, replacing the numerals with the correct ones for each place value
  I knew that lists were a thing that existed, so I googles how to make a list, and tried creating three simultanious ones
  One controlled place value, one the 1, 10, 100, and 1000, and one for the 5, 50, 500, and 5000 numerals 
  It took some fiddling to realize that I needed to clarify that it was using the list for i but once that clicked the rest was fairly easy  
  
 I'm sure there are other ways this code could be condensed, but I am quite proud of even getting it down to 30 lines, considering my original was around 200
