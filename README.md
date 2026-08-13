# IPTABLES_Documentation
This project is in its early stages.  Motivation for this project was to revisit the available documentation regarding IPTABLES before re-writing my personal scripts managing the IPTABLES firewall on my personal home desktop computer.  

The resulting documentation set will also offer a structured mechanism within which the refined learnings for such firewalls to be captured and stored for ongoing reference, as well as a vehicle to organize such knowledge in a cohesive manner.

To that end, HTML-based documentation for IPTABLES, using a grid-based approach presents tags that may be relevant for various scenarios at table states within each chain for the 3 dataflows, namely
- Outgoing,
- Incoming, and
- Forwarding.

The documentation grid for each of those packet flow streams have been defined with a uniform appearance in style and interraction.

The current effort is focused on publishing the appropriate guidance as applicable to each context-based IPTABLES target.

Anyone who feels that they have information (knowledge, insights, examples) which they would like to see included as part of this effort are invited to share their contributions.

# Approach
I have deliberately constructed the web pages such that there would not be any need for a web server to view the full set of documentation, if dropped into a directory anywhere on a Linux system.  I chose that approach because I did not want to open an http server only to handle my personal, desktop documentation.  That being said, the structure still lends itself to being correctly accessible if offered by such a server.

# Preview of Indexing Grids

**Documentation Grid for Outgoing Packet Stream**

<img width="570" height="498" alt="SNAPSHOT__OutgoingStream" src="https://github.com/user-attachments/assets/f4babf64-771f-4654-9e63-350b379682bf" />  

<hr>
**Documentation Grid for Incoming Packet Stream**

<img width="570" height="503" alt="SNAPSHOT__IncomingStream" src="https://github.com/user-attachments/assets/3fc9ba3f-9a13-44b0-b828-dd3026377f65" />  

<hr>
**Documentation Grid for Forwarding Packet Stream**

<img width="643" height="495" alt="SNAPSHOT__PacketForwarding" src="https://github.com/user-attachments/assets/12e83469-ba6f-45b5-8393-24042e2738f9" />  

# Preview of Pop-Up Guidance

<img width="578" height="632" alt="SNAPSHOT__Guidance__DROP__PRE_raw" src="https://github.com/user-attachments/assets/8aac3546-dd52-4535-a27e-c6cdb4ef099c" />


# Futures
[1] I am debating whether to add a click button to expand the documentation iframe to fill the viewport and click again to restore/close the documentation.

[2] I am debating whether to maintain an embedded-code approach, vs having JS and CSS extracted as shared code segments by all documents, to minimize the full size of the documentation set.  I am hesitant to pursue this approach because it would impose the irrevocable need for accessing via an http server which, as previously stated, I am loathe to endure.

[3] The Guidance documents will eventually offer a visual attribute for various scenarios to indicate whether the individual scenarios are applicable to the personal desktop computer context or to a multi-user service host.
