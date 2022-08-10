# Regex Tutorial: Everything You Need To Know

Welcome to a short tutorial on Regular Expressions, also known as Regex. Truth be told, there isn't really anything regular about regular expressions.
Personally I believe it is a play on words because it can seem extremely complex. The truth is that regular expressions looks irregular, but it is very easy to learn.
Are you ready? lets go!

## Summary

Regular Expressions also known as regex, is a universal coding expression that acts as a finder within data, code, and general information. It's very similar to using the finder tool
on your local device. What makes regex different is that it allows you to channel specific information that you are looking for based upon different characteristics such as character qauntity, 
character type, character range. This includes numbers, letters, special characters and even spacing. Regex allows you to get really particular in finding what you're looking for, or even setting access barriers for when you're collecting information. Remember a time when you were creating a password and there was already something in your screen that let you know about the parameters set and rules you had to follow for your website to approve it? This is just the surface of the power and particularity of regex.



# Let's practice with matching an Email

 The expression below is set to match an email


 <code> – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ </code>


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)

There are other important pieces that also contribute to regular expressions but we only have included the ones that can be applied to the example we've created below.


## Regex Components

### Anchors

First let's address the anchors, the anchors within the listed regex are: <code> $ and ^</code>. 

The <code> $ </code> is an anchor that traditionally indicates the stopping point to characters which precede it. These characters are being actively used to find the matching email.

The <code> ^ </code> is an anchor that traditionally indicates the beginning point to characters which come after it. These characters are being actively used to find the matching email as well.

These anchors solidify the beginning and end of what the computer should look for to match the email. 

### Quantifiers

Quantifers traditionally help narrow and intesify the limits that are specific to the string you're looking for, in our case an email! When matching an email, the code we have above seems to indicate that the matching email is limited to 2 - 6 characters.

<code> {2,6} </code> this is the primary and in this case the only quanitfier in this expression.


### Grouping Constructs

 <code> () () () </code> 

 Within our expression we have about 3 grouping constructs. These grouping constructs are put in place to idenitfy and distinguish different groups within the expression. In this case our email match is being separated into three groups of possibilities. Our matching email will have to pass through each of those three groups.

### Bracket Expressions

<code> [] [] [] </code> 

Bracket expressions signify all the characters that you wish to match. Whatever expressions are within the bracket is what will be searched and compared to whatever we wish to find. In our case we have 3 brackets and they all wish to bring together different parts of the email.

### Character Classes

<code> /da, ., </code> 

Character classes consist of different general rules that must be followed. 

<code> /da </code> 

The class above signifies any numeric character between 0 and 9. Similar to the bracket expression [0-9]


## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
