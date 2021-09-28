# Resolución y explicación de Cap y Seal (HTB)

This repository contains my thesis (Master's project) for the Master's Degree in Computer Security and Ethical Hacking at [CICE](https://www.cice.es/).

**This thesis is in Spanish**. No English version available.

## Author

[Víctor Nieves Sánchez](https://www.linkedin.com/in/victor-nieves-s%C3%A1nchez/)

## Abstract

In the technology industry, cybersecurity is very important. Companies are increasingly focused on ensuring that their various applications, projects and services are secure; that they are protected from internal and external threats and vulnerabilities.

On the other hand, having more and more smart devices connected to the network, mobile applications, web portals and web services provides hackers with a huge playing field, and a very striking scenario for malicious acts. Fortunately, not all hackers are bad: ethical hackers, those who use their skills to improve network security, are increasingly acclaimed by companies.

With the aim of introducing me to the world of cybersecurity and hacking, this work was born. As a ``novice`` in the field, I have found many tools and articles to read that allow me to learn and improve my knowledge and skills. One of the most fun and easy (to use) tools I have found is Hack The Box and the Capture The Flag style events and challenges. These challenges allow you to increase your knowledge in different technologies, such as web, mobile or in certain fields like cryptography or reversing.

In this document I will explain the Hack The Box platform and solve two machines on the platform; I will share the findings and results obtained, as well as the reasons behind the decisions made.

**Keywords**: Hacking, Ethical Hacking, Cybersecurity, Hack The Box, Capture The Flag, Certified Ethical Hacker ...

## Requirements

1. Install **_LaTex_** (also Spanish language).

```bash
sudo apt install texlive-full texlive-lang-spanish
```

## Generate the PDF file

Just run the _Makefile_ with:

```bash
make
```

More info:

```bash
This Makefile generates the file TFM_VICTOR_NIEVES_SANCHEZ.pdf.
Author: Víctor Nieves Sánchez
Mail: vnievess@gmail.com

help:			Show this help.
compile: 		Compiles the main .tex.
generate_bibliography:	Generates the bibliography. 
generate_glossary:	Generates the glossary and the list of acronyms.
recompile_and_rename:	Recompiles the .tex and renames the PDF file.
clean:			Clean output files.
```
