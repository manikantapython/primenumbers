#
# README.txt for $ORACLE_HOME/j2ee/home/jazn/config
#

Introduction
------------

This directory contains sample JAZN-related configuration files.

Description
-----------

java2.policy
- The Java 2 policy file. This file has been pre-configured to contain
  grants necessary for OC4J to be launched with SecurityManager enabled.
- You'll need to edit this file to reflect your local settings.

java2all.policy
- a simplified Java2 policy file designed to help you get 
pass Java2-based code based policy 
- NOT recommended for any production environments

jazn.xml
- The JAZN-XML configuration file
- You *may* need to edit this file to reflect your local settings.

jazn-data0.xml
- A skeleton JAZN data file

jazn-data.xml
- A sample JAZN data file containing a simple realm (jazn.com)
- This realm is designed to mirror the default settings in principals.xml

jazn-data1.xml
- A sample JAZN data file containing a simple realm (sample_subrealm)
- This realm is designed to mirror the JAZN-LDAP demo realm with the same name.
	

