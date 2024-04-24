                                            JavaScript
                                          Assignment 5
# 1.Write short notes on string methods with code examples
# a.toLowerCase()
# b.toUpperCase()
# c.subString()
# d.replace()
# e.trim()
# f.split()
# g.slice()
# Ans:
# a. let str="HEY  THERE"
# console.log(str.toLowerCase());
# b.let str="hey there"
# console.log(str.toUpperCase());
# c:-let str="hey there"
# console.log(str.substring(0,4));
# d:- let str="hey there"
# console.log(str.replace("hey", "hi"));
# e:-let str=" hey there  "
# console.log(str.trim());
# f:-let str=" hey there "
# console.log(str.split(" "));
# g:-let str=" hey there "
# console.log(str.slice(1,5));

# 2.create a simple app that takes the user’s name and greets him/her after capitalizing the first letter of the user’s name and changing the rest of the letters into lowercase (toUpperCase(), toLowerCase(), slice(), length property, string concatenation)

# Ans:let yourName=prompt("enter your name");
# let firstLetter=yourName.slice(0,1)
# let upperCasedLetter=firstLetter.toUpperCase()
# let secondLetter=yourName.slice(1,yourName.length)
# let lowerCasedLetter=secondLetter.toLowerCase()
# let fullName=upperCasedLetter+lowerCasedLetter
# alert("hii" +fullName)