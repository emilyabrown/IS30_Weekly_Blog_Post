#### Weekly Weblog - Week1 the history of the Internet 

------

For this week's lecture, we have read five articles on topics of  how does the derivation of technology affects the social ideology, specifically the invention of tachograph ( [Technology and Ideology: The Case of the Telegraph](http://faculty.georgetown.edu/irvinem/theory/Carey-TechnologyandIdeology.pdf) by James W. Carey, [The Master Switch](https://www.amazon.com/Master-Switch-Rise-Information-Empires/dp/0307390993) by Tim Wu)  and the debates has been centered around how internet should be and what regulations should be posed on it. ([Engineering a Principle: End-to-End in the Design of the Internet](https://www.jstor.org/stable/25474452?seq=2#metadata_info_tab_contents ) by Tarleton Gillespie] [Not The Internet, but This Internet](https://www.dourish.com/publications/2015/NotTheInternet.pdf) by Paul Dourish and [How to Build a low-tech Internet](https://www.lowtechmagazine.com/2015/10/how-to-build-a-low-tech-internet.html) from LOW-TECH MAGAZINE )



In the article written by James Carey, the author argued the effect of telegraph has been overlooked for the following reasons. The monopoly of Western Union dominating telegraph was followed as a prototype of many industrial enterprises. Telegraph has redefined the dentition of communication, communication is not bounded to the idea of transportation anymore ever since the invention of telegraph because with telegraph, messages and information can be transmitted without the physical movement of any transportation. Carey backed up his argument with an example of rail road signal, the using of telegraph to send signal for controlling rolling stock switches effectively increased the productive of communication.  Telegraph also reformed the business relationship from personal to impersonal, business decisions do not have to be mediated face to face. Telegraph made the product information to be transparent thus reduced the arbitrage by making geography irrelevant. (Carey)



In the book of The Master Switch written by Professor Wu, he described how rising of novel technology can widely affect the social transformation. In his book, he used the metaphor cycle to describe the oscillation pattern of information industries between open and closed (Wu 6). To my understanding, the cycle refers to  the formation of new technology , the consolidation and monopolization of that technology from industrial companies and the possibly the falling of the technology. Professor Wu used the example of Bell telegraph company transformed into one of the most profound industrial monopoly AT&T. (Wu) This cycle reminds me of the wax and wane of AI, where it starts from a philosophical point describing how programs can be written in a way imitate human behaviors, at first, it posed a hype where people pictured the future of AI as super intelligence. Then people slowly lost promises and interested of AI because they didn't see the super intelligence happen. Today, AI has became one of the most influential technology in technical fields including computer vision, robotics, natural language processing etc. Most of the tech giants uses it for product development. To me, the evolution of AI can be thought as an example of the cycle. 



In the Paper of End to End design principle of the network , the author Gillespie introduced the term "End to End" and how does the term transform how people think of the network and how does it introduced disputes interns of packet-switching. Packet switching is a technique that groups data into chances so that the messages can be efficiently transmitted through the network. There are few benefits of packets, one is that data can be transmitted trough a pipeline where multiple packets can be transmitted simultaneously. The other is it produce a much sharing. The debates around the Internet centers around the data integrity, how does the network make sure message sending is complete through the network. One solution is to distribute the transmission task locally through a peer to peer network , each intermediate point is responsible for checking the integrity of the received packets. The downside of this approach is that it blows up the Internet by having to reserve a temporary copy of the original message in case data is lost somewhere in the network, thus the overhead of copying and checking the packets doesn't benefit from the principle of creating packets in the first place. Thus the design of End to End architecture came to pass, the idea being data integrity checking happens only at the end points of the network in which the intermediate network only acts as a transportation that knows nothing about the content of the message. This approach greatly reduced the overhead of blowing up the network and limited the redundant checking through intermediate layer. However it has its downside as well, in contrast to the peer to peer design, if the data is lost somewhere in the End to End network, the transmission process has to start over again where as in the  peer to peer network, the resending message only need to be reproduced through the part of the network where the data has been lost. In addition, End to End network doesn't shine when it comes to countries that imposes Internet censorship well since there isn't a "middle man" in between the network to control the data transmission, same problem happens for copyright. (Gillespie)



In the paper written by Dourish, the author specifically talked about the relationship between Internet censorship and decentralized democracy.  The arrival of internet is attributed to centralized servers, each services provide is responsible for hosting the services for customers, the major problem comes into the throttling and data privacy issues. Internet providers nowadays have too much power and control over the data coming through the internet and companies even monetize user's data for profiting which brings the emerging needs of having decentralized network. 



In the article How to build a low-tech internet, the author introduced low tech internet starting from comparing the internet in richer and poor countries, poor countries tend to have low-tech internet which uses cheeper networks less resources and computing powers but results in slower speed. The article introduced several low cost and energy efficient low-tech internet, including WIFI-based Long Distance Networks, sneakernet and resilient networks most low-tech network are implemented based on WIFI, one limitation of WIFI is the communication usually happens in a distance within 30 meters, the long-distance network allows the network communication distance to be expanded to over 1000 kilometers. The realization of this technique in many countries introduced major benefits to the country, India, for instance, with this technique, doctors can remotely examine and support patients in poor regions that has fewer trained health technicians. In rich countries from Europe like Spain, users build and maintain such Wifi-Based network themselves and the network expands as more and more users joins the network. One significant advantage of low-cost network over high-cost network is that while high-cost network provides more efficient services in terms of high quality and high speed, it relies on a condition where the power supply has to be substantial and robust, low-tech networks remain to work even when supply is interrupted. (Decker)





**References**

Carey, James W. “Technology and Ideology: The Case of the Telegraph | Prospects.” *Cambridge Core*, Cambridge University Press, 30 July 2009, www.cambridge.org/core/journals/prospects/article/technology-and-ideology-the-case-of-the-telegraph/9C32F047433D0E498722E5248CD31B51.



Wu, Tim. *The Master Switch: the Rise and Fall of Information Empires*. Atlantic Books, 2012.



*Packet Switching*, erg.abdn.ac.uk/users/gorry/course/intro-pages/ps.html.



Gillespie, Tarleton. “Engineering a Principle: 'End-to-End' in the Design of the Internet - Tarleton Gillespie, 2006.” *SAGE Journals*, journals.sagepub.com/doi/10.1177/0306312706056047.



Decker, Kris De. “How to Build a Low-Tech Internet.” *LOW-TECH MAGAZINE*, www.lowtechmagazine.com/2015/10/how-to-build-a-low-tech-internet.html.
