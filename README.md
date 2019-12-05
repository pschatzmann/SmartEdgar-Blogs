# SmartEdgar-Blogs

In the US, all companies, foreign and domestic, are required to file registration statements, periodic reports, and other forms electronically through EDGAR. Anyone can access and download this information for free.

This goal of this project is to make this information accessible in an easy way so that it can be used by any Data Science functionality. It consists of the following core functionality

A Java API
- which provides Company information and Company filings from the EDGAR site
- which implements a XBRL parser (which supports XBRL an iXBRL)
- for Reporting on Summary Information
- for Reporting on Company KPIs
- REST Services
- to access XBRL files
- to access consolidated numerical information which are stored in a Database
- which provides financial KPIs for a selected company
- Automatic Download of the latest XBRL files and import them into a SQL database
