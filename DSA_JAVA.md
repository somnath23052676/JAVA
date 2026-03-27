Integer.MIN_VALUE - for assigning minimum value 
Integer.MAX_VALUE - for assigning maximum value 

StringBuilder sb = new StringBuilder() - creates an empty StringBuilder
StringBuilder sb = new StringBuilder(s) [where 's' is a string] - creates a StringBuilder using the string 's'
sb.append("hello") - appends "hello to the end of the string
sb.insert(5 , "hello") - inserts 'hello' at the 5th index (0 indexing)
sb.delete(5,10) - deletes characters from index 5 to 9 (excluding 10)  eg 'abcdefghijk' here from index 5 ('f') to index 9 ('j') will be deleted ---> after deletion - 'abcdek'
sb.deleteCharAt(index) - deletes the character at the 'index'
sb.replace(5,10,"world") - replaces the characters from index 5 to index 9 with "world"
sb.reverse() - reverses the characters of the StringBuilder
sb.length() - length of StringBuilder
sb.charAt(index) - selects character at 'index' 
sb.setCharAt(index , 'y' ) - sets character at index from the previous one to new one('y')

