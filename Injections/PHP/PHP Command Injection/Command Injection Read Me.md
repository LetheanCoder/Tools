Simple PHP Command Injection

•OWASP Severity Level: 1 

•What is it: Command Injection. 

•Happens with: Web Appplications. 

•When does it happen: When server-side code in web app makes a system call on hosting machine. 

•What does it do: Allows attacker to use system made call to execute OS commands on the server.

•What this code does: checks if parameter "commandString" is set •if so, variable "$command_string" gets what was passed into input field •goes into try block to execute function "passthru(command_string)"
