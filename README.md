# Dates passwords generator and passwords combinator

## Description

This application can:

- Genrate dates password in differents formats like:
  - ddmmyyyy  --> 01022024, 01@02#2024, @01022024- 
  - yyyymmdd  --> 20240201, 20/24/0201, 20240201@
  - 2yyyy     --> 20242024, 19852023, 1985@2023
  - 3yyyy     --> 202120222025, 2021@2022@2025, *202120222025*
  - ddmm2yyyy --> 010220242024, 010220241995, 01022024\1995
  
- Add text to the begining or/and end of every lines of list

- Combine two lists of passwords, combine every word of the right list with each word of the left list

- Generate passwords and cracking with Aircrack-ng by using cap file, you need to download Aircrack-ng 
  and choosing the path of Aircrack-ng.exe in the application, and the path of cap file that contain the handshake or PMKID captured by using airodump-ng

you need to download aircrack-ng from https://www.aircrack-ng.org for windows, extract the archive and specify the path to aircrack-ng.exe

This application is coded with Lazarus on windows 10

## Disclaimer

I am in no way responsible for using this application for illegal purposes, 
you are solely responsible for your actions.
