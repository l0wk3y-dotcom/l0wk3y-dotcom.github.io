# Cybersecurity Tools and Concepts

## Table of Contents

- [Introduction](#introduction)
- [Game Concept for Learning Python](#game-concept-for-learning-python)
- [Web Directory Bruteforcer](#web-directory-bruteforcer)
- [Active Directory Exploitation](#active-directory-exploitation)
  - [Exploiting GPOs](#exploiting-gpos)
  - [Certificate Template Misconfigurations](#certificate-template-misconfigurations)
  - [Exploiting AD Users](#exploiting-ad-users)
- [Networking Concepts](#networking-concepts)
  - [Multicast DNS (mDNS)](#multicast-dns-mdns)
  - [NTLM vs Kerberos](#ntlm-vs-kerberos)
- [Interview Preparation](#interview-preparation)
- [Offensive Security Project: Rubber Ducky](#offensive-security-project-rubber-ducky)
- [Current Status](#current-status)

## Introduction

This repository is a collection of various cybersecurity tools, projects, and concepts that I have been working on. It includes a game concept for learning Python, a web directory bruteforcer, and detailed notes on different Active Directory exploitation techniques.

## Game Concept for Learning Python

### Overview
A puzzle game designed to teach basic programming skills in Python. The game targets a wide audience and covers fundamental programming concepts.

### Features
- Interactive puzzles that require Python code to solve.
- Gradual increase in difficulty to match learning progress.
- Real-time feedback on code submissions.

## Web Directory Bruteforcer

### Overview
A Python-based web directory bruteforcer inspired by ffuf. This tool helps in identifying hidden directories and files on web servers.

### Usage
```bash
python bruteforcer.py -u <target_url> -w <wordlist>
