readme.md

# ZoomMeetings
    Connects to select Zoom meeting.
        Meetings -> dictionary of string, array of string
        key is name of meeting
        value is [meeting ID, meeting passcode]
    Meeting is automatically selected
        by Revature.Morning.Meetings automation
        by RevatureAfternoonMeetings automation
    If meeting is not automatically selected
        User selects meeting from menu
    Opens Zoom desktop app
    Enters meeting ID
    Sets the displayed name according to meeting guidelines
    Enters meeting passcode
        Try enter passcode
        Catch if exception is thrown
            rethrow exception
        Finally click join meeting