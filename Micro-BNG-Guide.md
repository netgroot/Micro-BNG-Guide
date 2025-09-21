# Micro-BNG-Guide
Micro BNG Guide 

**Guide to Monitor User Traffic in BNG Sessions**

1. **Find Interface Name:**
   - Execute the command to display session details for a specific username:
     ```
     show bng sessions username [insert-username-here]
     ```
   - Locate the 'ifname' in the output table corresponding to the username you queried.

2. **Monitor Traffic:**
   - Use the identified interface name to monitor traffic:
     ```
     monitor traffic interface [insert-ifname-here]
     ```
   - Replace `[insert-ifname-here]` with the actual interface name from the previous step.

By following these steps, you can effectively monitor the user traffic on a broadband network gateway session.
