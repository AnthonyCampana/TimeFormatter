# TimeFormatter

Given a date String of the format given by the Twitter API, returns a display-formatted String representing the relative time difference, e.g. "2m", "6d", "23 May", "1 Jan 2014" depending on how great the time difference between now and the given date is. This, as of 2016-06-29, matches the behavior of the official Twitter app.

## Usage
Just copy TimeFormatter.java into a Java class in your project, then call
    String formattedTime = TimeFormatter.getTimeDifference(String dateString);
To turn a Twitter API-returned dateString into a String properly formatted for display. 
