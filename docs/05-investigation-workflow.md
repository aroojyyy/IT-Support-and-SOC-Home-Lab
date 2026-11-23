# Security Monitoring and Investigation

I used Splunk Enterprise to explore incoming Windows events and investigated security related activities.

## Failed Authentication Investigation

I performed controlled failed login attempts to generate Windows Security Event ID "4625".

## Investigation Process
1. I accessed the incoming Windows security logs in Splunk.
2. searched for failed authentication events.
3. Identified Event ID "4625"
4. reviewed the available event details and timestamps.
5. examined the records to understand failed login activity.

## SPL Searches
I used SPL searches to review Windows authentication activity, including failed logons and logoff events.
