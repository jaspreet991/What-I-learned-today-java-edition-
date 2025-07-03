# What-I-learned-today-java-edition- DAY1
Things I am learning on my java journey!! 
Today's topic: Functions!
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Notes:
1) Diffference between '==' and '.equals' :
'==' is used to compare memory addresses and '.equals' compares the actual content of the Strings.
for eg.
String a = new String("hello");
String b = new String("hello");
a==b; //false, coz they are storedin different addresses in memory even tho they have the same value.
a.equals(b) // true, coz .equals() method compares the actual contents, which are same in this case!
