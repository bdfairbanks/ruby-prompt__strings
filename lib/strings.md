---
title: Strings
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a String?

Strings are objects conotated by ""s and ''s.

# What are some examples of information that would be Strings as opposed to some other data type?

Strings are the only object I have yet seen in ruby that are purely text. Because of this it can be used to name processes and "talk" to the user

# What is one way, using Ruby, to retrieve the 6th character in a String like `"Ada Lovelace"`? How about the 8th character? What happens if you try to retrieve the value of the _99th_ character (Or any character that doesn't exist)?

I used the [] method, which is placed at the end of the string and the values 6, 8, and 99 are pluged inside the square brackets to retrieve the coresponding character.
(the counting begins at zero and the method counts spaces as charecters) Retrieving the 99th charecter returns not an error as I supposed, but a space, like the one returned when 
I set the method to retrieve the space between the name.

# The previous question asks about finding, for example, the 6th character in a String. Is it possible to find the **-6th** (Notice the negative symbol!) character in a String? What does that even mean?

Asking for the -nth number tells the method to begin counting at the end of the string, and count backwords. Cool.

# What is one way, using Ruby, to replace certain characters in a string with some other set of characters? For example, given `"Sumeet Jain"`, how would you replace all of the `e` characters in my name with exclamation marks? (So it would be `"Sum!!t Jain"`.)

I used the .gsub! method, which ends up looking like puts 'Sumeet Jain'.gsub!('e', '!')
