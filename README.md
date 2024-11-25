Hello! My name is Joseph Alexander. This is my lab write up for learning the SIEM tool Splunk.

Objective: Learn what splunk is and it's different components. 

What is Splunk? 
Splunk is a Security Information and Event Management (SIEM) platform designed for the collection, storage, and analysis of machine data. It offers a range of tools for data analysis, including search, correlation, and visualization. This powerful platform can be utilized by organizations of any size to enhance their IT operations and strengthen their security posture.

Components
Splunk consists of three main components, an Indexer, Search Head, and Forwarder
1) Splunk Forwarder essentialy sends or "forwards" information from the traffic on a network and sends it to the Splunk instance. Note: This includes web server traffic, windows logs and linux logs.
2) Splunk Indexer Recieved the information from the forwarder and "normalizes" for humans to be able to read them by determining the data type and stores them as events. These events are then easy to search for and analyze.
3) Splunk Search head is basically a way to search for the data/events that Splunk Indexer stores. This search tool uses a languange that is specific to splunk called SPL (Splunk Processing Language). This will send a request back to the indexer and return in the form of field value pairs.

Navigation 
During my time in the Splunk lab, I spent most of my time learning to navigate through the different sections of the platform. I first started with the Splunk Bar, where you can find your messages, settings, and activity, along with a search bar. I also navigated using the Apps Bar, which shows all the applications installed for the Splunk instances. This means that each organization will have its own proprietary applications installed so that Splunk can create events to meet the needs of that business. The most important part of Splunk is the Splunk Dashboard. In the lab, no dashboards are displayed by default and you can choose from a wide range of dashboards. These dashboards can show a plethora of valuable data that is used to give a visual for a better understanding. 

Conclusion 
In this lab, I gained basic knowledge of the Splunk platform. Splunk is designed to collect, store, and analyze data. This offers a wide range of tools for data analysis, including search, correlation and visualization. This platform is highly beneficial and even critical to organizations of all sizes when it comes to strengthening their security posture. 
