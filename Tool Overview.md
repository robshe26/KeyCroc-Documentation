# Key Croc - Tool Overview 

 - THis document holds a description of the tool `Key Croc`, and its uses.

 ## Overview

 The Key Croc is a stelthy hardware keylogger and attack prlatform. It acts as a physical man-in-the-middle between a jeyboard and a computer that captures every keystroke typed. Due to it being a hardware tool, it remains invisbile to the target computer's operating system. 

## How it Works: The Hardware

The Key Croc mimics a standard USB device and sits physically between the keyboard and the target machine.
- Physical Steup: You plug the target's keyboard into the USB port of the Key Croc, and then plug the Key Croc's connecter into the computer
- Passthrough: It passes all keyboard data to the computer. To the user and the PC, it appears as a legitmite Human Interface Device.
- The Data Collection: While the user types, the Key Croc records ever character to its internal storage. It can also be programmed to trigger specific actions when it detetects "pattern matches" like passwords or specific usernames.

## Capabilities

The Key Croc is designed for logging and offensive attacks 

A. Keystroke Injection (Payloads)
 - It can act as a "Rubber Ducky", injecting its own keystrokes back into the target computer.

B. Pattern Matching and Exfiltration 
 - You can define "triggers" for sensitve strings. Once a keyword is matched, the Key Croc can save that specific data to a seperate file or send a notification.

C. Remote Access and Cloud C2
 - Since the tool is equipped with Wi-Fi, the Key Croc can connect with Hak5's Cloud C2 Platform. This allows you to:
    - Live-view keystrokes as they happen from a remote dashboard.
    - Inject payloads or change configurations remotely
    - Exfiltrate logs without needing to physically retrieve the device.

## Primary Use Cases

- Penetration testing:
    - Physical engagment where an attacker can quickly plug the evice into the back of a workstation to gian long-term credential access.
- Social Engineering:
    - Testing an oganization's internal secuirty by leaving the hardware in an office to see if emplyees will plug it in
- Security Audting:
    - Monitoring administrative consoles where software monitoring tools are not possible 

