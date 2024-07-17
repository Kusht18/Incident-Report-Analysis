

### Description of Project:
Given a security event create a plan to improve your fictional company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). 

# Incident Report Analysis

<table>
  <tr>
   <td><strong>Summary</strong>
   </td>
   <td colspan="3" >Organizations networks suddenly stopped responding. The internal traffic could not access any of the networks resources. Security team identified the issue was a result of a DDoS attack from a flood of ICMP packets. Team responded by blocking all incoming ICMP packets and stopping non-critical network services so critical network services could be restored.
   </td>
  </tr>
  <tr>
   <td>Identify
   </td>
   <td colspan="3" >Cybersecurity team found that flood of ICMP pings had been sent into the company’s network through a firewall. The malicious actor was able to overwhelm the company’s network using a DDoS attack. The entire internal network was affected. 
   </td>
  </tr>
  <tr>
   <td>Protect
   </td>
   <td colspan="3" >The team implemented a firewall rule to limit the number of ICMP packets from getting through. IDS/IPS system has been implemented to detect and filter out suspicious iCMP traffic.
   </td>
  </tr>
  <tr>
   <td>Detect
   </td>
   <td colspan="3" >To prevent similar future security events the team implemented IP address verification on the firewall to check for IP spoofing on incoming ICMP packet. Added network monitoring software to detent abornmalities in traffic patterns. 
   </td>
  </tr>
  <tr>
   <td>Respond
   </td>
   <td colspan="3" >For future events the security team will isolate the affected systems and restore any critical systems affected by the event. Team should analyze logs and report incidents to management.
   </td>
  </tr>
  <tr>
   <td>Recover
   </td>
   <td colspan="3" >To recover from a ICMP flood attack network services should be restored to normal operating state. Future attacks can be blocked with new firewall policies. Non-critical network services should be stopped to reduce network traffic. Once flood of ICMP packets have timed out the non-critical services should be brought back online.
   </td>
  </tr>
</table>
