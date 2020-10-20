# riskenginecall
Python script to poll a risk engine and then parse and make a decision based on conditional logic.
I have added a while loop to run until a match is made and then execute a logout of APM sessions.
This can be used to augment Zero Trust HTTP connector in IAP.
HTTP Connector does not fire on VDI flows, so RDP sessions will not be logged off or asked for step up auth.
This forces a logoff and users can log back in and see a warning banner and be asked for additional auth.
