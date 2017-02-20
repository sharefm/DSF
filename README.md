Data Science Project Proposal 
=============================

Proposed by: 
Sharef Mustafa & Loai Abdallatif    


                                           
# Introduction

Web Sites security is a major concern these days, even though many security controls are applied, still there will be always new types of attacks.

Traditional security controls ( IPS, WAF, Apache Hardening, etc…) depends on predefined attack signatures which been inspected in limited time window.

In this project, we are going to investigate the logs of three security controls applied on one website in order to reveal attack types that are not detected by the current controls. 

# Context

The Datasets that we are going to analyze from three sources which are:
1.	Intrusion prevention system(IPS) firewall
2.	Web Application Firewall (WAF)
3.	Apache Web Server.
The above three sources contain data collected for the period Jan 04, 2017 till Feb 19, 2017. 

# Content

Each row of the logs in the three data sets corresponds to one http request, and each row has its own time stamp.
Methodology
In our project, we will investigate the relationship between the source Address, http request URL, and Request Timestamp among the three data sets in order to distinguish the legitimate requests and isolate other requests for further analyses specially if these isolated requests passed through existing security controls. 
