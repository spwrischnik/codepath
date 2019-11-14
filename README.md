# codepath

Username Enumeration: In the green site, attempting to log in with a valid
		      username bolds the text "Log in was unsuccessful." 
		      The text is normal when logging in with an 
		      invalid username.

Insecure Direct Object Reference: In the red site, when directly typing a 
				  sequential number after "php?id=", 
				  the page shows info that's not publicly 
				  available for viewing. 

SQL Injection: In the blue site, an error displaying "database query failed"
	       appears when typing a ' to terminate an sql command. The red 
	       and green sites simply redirect. 

Cross-Site Scripting: In the green site, typing in an html alert message in the 
		      feedback section will run the alert message when the admin
		      checks the feedback section. 

Session Hijacking: In the blue site, a user on a different browser than the
		   admin can change their session id to the admin's session id 
		   to gain admin access and privileges.