# TwilioMVC

A simple app using Twilio to send/receive requests and log the history of the requests.

An EnvironmentVariables.cs file is needed in the Models directory.
You will need to add Twilio Account SID and Auth Tokens.
```
namespace TwilioMVC.Models
{
    public class EnvironmentVariables
    {
        public static string AccountSid = "KEY_HERE";
        public static string AuthToken = "KEY_HERE";
    }
}
```
