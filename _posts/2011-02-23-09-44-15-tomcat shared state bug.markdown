# Tomcat #

**THIS WILL HURT YOU**

**`private static final DateFormat dateFormatter = new SimpleDateFormat();`**

`SimpleDateFormat` isn't threadsafe. Instance shared between all threads accessing code

*Just a matter of time till...*