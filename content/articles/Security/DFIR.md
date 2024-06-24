---
title: "Digital Forensics First Responder Tool"
date: "2019-09-13"
categories:
 - "Security"
description: Defence Against the Dark Arts (abbreviated as DADA) is a subject taught at Hogwarts School of Witchcraft and Wizardry and Ilvermorny School of Witchcraft and Wizardry. In this class, students study and learn how to defend themselves against all aspects of the Dark Arts, including dark creatures, curses, hexes and jinxes (dark charms), and duelling.
---
### Digital Forensics First Responder Tool

In on my university course "Digital Forensics". I choose a project on developing
a First Responder Tool which can act as a chain of custody tool. In this project
the challenge was to create a Linux artifacts collection such as volatile and non volatile
evidence. The volatile evidence included:-
> 1. Ip address assigned
> 2. Network Statistics.
> 3. Mount Points
> 4. Disk Usage.
> 5. Running system processes
> 6. Startup and running processes
> 7. User Login informations.

and the non volatile evidence included:-
> 1. Boot Images
> 2. Memory informations.
> 3. CPU utilisation.

These informations in linux system holds informations that can help aid
forensics team investigate on a case. For example if an external usb was used
to perform some illegal transactions and that the suspect is claming of no involvement in it
the Mount points and user login informations can provide the evidence on whether the
supect was involved or not in the court of law.

All the informations that was gathered would be saved as as single log file which can then
be encrypted and saved for chain of custody.

  * * *

    --- University of Technology Sydney 48436 Digital Forensics - Spring 2018 Assignment---
         ______
             .-'   _ `-.
           .'     | |    `.
          /       | |     \
         ;        | |      ;`
         |        | |      |;
         ;        | |_ _ _ ;|
         '\       |_ _ _ _/ ;inux Forensics...
          \`.           .' /
           `.`-._____.-' .'
             / /`_____.-'
            / / /
           / / /
          / / /
         / / /
         \__/
    Dependencies:
    Python 3
        whois

     Contributors:
                1. Gurparteek Singh (OYE!)
                2. Muhammad Hamza Khalid (SPY!!)
                3. Samrat Pant (Gurkha!!!)
                4. Vishal Uniyal (Shakuna!!! )

       ---Disclaimer: Please have a written approval from owner or search warrant if you use this tool---

This Tool was designed to be logged in by a Digital forensics Responders whose name would be used to sign the
evidece in the log.

I along with my group mates Gurprateek, Hamza and Vishal contribute in the development and it was written in python
The source code is avilable in github at (https://github.com/samurato/DigitalForensics)