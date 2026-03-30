# it-support-simulation
IT Support Simulation Script
Scenario: Microsoft Outlook is not launching

Agent: Good day. Thank you for contacting IT Support. My name is Nandi Zulu. How 
       may I assist you today?

Customer: Hi, my Outlook is not opening. When I click on it, nothing happens.
Agent: I’m sorry to hear that. I’ll assist you with this.
      Before we begin, I’d like to understand the impact of the issue.
      • Is this affecting only you or other colleagues as well?
      • Are you able to access your emails in any other way?
      • How urgent is this for your work right now?

Customer: It’s just me, I can’t access emails at all and It’s urgent, I need to respond to 
clients
Agent: Thank you. Are you using a work (corporate) computer or a personal device?

Customer: It’s a work laptop.
Agent: Thank you for confirming. Since this is affecting your work and you currently 
       don’t have access to emails, I will prioritize resolving this as quickly as possible.
       Let’s start with a quick check. Please restart your computer and try opening Outlook 
       again.

Customer: I’ve restarted, but it’s still not opening.
Agent: Alright, let’s try opening Outlook in Safe Mode.
      • Press Windows + R
      • Type: outlook.exe /safe
      • Then press Enter
      
Customer: Okay, it opened.
Agent: Great, that helps us identify the issue. This usually means an add-in may be 
      causing the problem. Let’s disable the add-ins:
      • Click File
      • Go to Options
      • Select Add-ins
      • At the bottom, click Go next to COM Add-ins
      • Uncheck all add-ins and click OK
Customer: Done.
Agent: Please close Outlook and open it normally again.

Customer: It’s working now!
Agent: That’s great to hear. The issue was caused by one of the add-ins preventing 
       Outlook from starting properly. If the issue happens again, we may need to identify the 
       specific add-in causing it. Is there anything else I can assist you with today

Customer: No, that’s all. Thank you.
