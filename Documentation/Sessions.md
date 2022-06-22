# Sessions
The website both does and does not use sessions, it depends on browser and theme.

## When are sessions not used?
Sessions are not initialized for users who are forced to use the text-based theme, or opt to use the text-based theme.

## What is the session used for?
Quite a lot of things, every visitor where applicable is assigned a unique session, depending on the theme in use it will temporarily store various data related to the website and its functions to give the user a much better experience.

## Garbage Collection / Session Destruction
Once in a while, the garbage collector will sweep the sessions and look for inactive sessions and destroy these, the same applies to when a user decides to log out.
