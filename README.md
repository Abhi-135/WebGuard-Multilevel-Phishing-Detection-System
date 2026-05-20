# WebGuard – Multi-Layer Phishing Detection System

WebGuard is a Java-based phishing detection web application that analyzes emails and URLs using multiple detection layers.

## Technologies Used
- Core Java
- JSP
- Servlets
- JDBC / MySQL
- Supabase
- VirusTotal API
- Apache Tomcat

## Features
- Email phishing detection
- URL scanning
- Keyword-based detection
- Pattern-based phishing analysis
- URL structural analysis
- Sender verification
- VirusTotal-based external verification
- Safe, Suspicious, and Danger classification

## Detection Layers
1. Layer 1: Keyword detection and sender brand verification
2. Layer 2: Pattern analysis using regex
3. Layer 3: URL structural analysis
4. External verification using VirusTotal API

## How to Run
1. Import the project into Eclipse.
2. Configure Apache Tomcat.
3. Add your Supabase and VirusTotal API keys in Config.java.
4. Run the project on Tomcat.
5. Open the application in browser.
