Hello! My name is Joseph Alexander. This is my lab write up for learning the SIEM tool Splunk.

Objective: Learn what splunk is and it's different components. 

What is Splunk? 
Splunk is a Security Information and Event Management (SIEM) platform designed for the collection, storage, and analysis of machine data. It offers a range of tools for data analysis, including search, correlation, and visualization. This powerful platform can be utilized by organizations of any size to enhance their IT operations and strengthen their security posture.

Components
Splunk consists of three main components, an Indexer, Search Head, and Forwarder
1) Splunk Forwarder essentialy sends or "forwards" information from the traffic on a network and sends it to the Splunk instance. Note: This includes web server traffic, windows logs and linux logs.
2) Splunk Indexer Recieved the information from the forwarder and "normalizes" for humans to be able to read them by determining the data type and stores them as events. These events are then easy to search for and analyze.
3) Splunk Search head is basically a way to search for the data/events that Splunk Indexer stores. This search tool uses a languange that is specific to splunk called SPL
