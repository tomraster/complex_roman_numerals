# complex_roman_numerals

Most software can easily translate Roman into Arabic numerals (0,1,2...). However, some historic documents contain Roman numerals that would be considered incorrect and, hence, 'intranslatable' by software. 

For example, iiiCLii would produce an error in R's as.numeric(as.roman()), while in the historic document, it simply means 3*C + Lii, i.e. 3"multiply"100+52=352.
