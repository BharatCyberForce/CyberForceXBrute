# CyberForceXBrute
## Multi-Website Brute Force Tool
This is a powerful and efficient multi-website brute force tool designed to quickly identify weak credentials across various WordPress websites simultaneously. With its multi-threading capabilities and auto-combination of usernames with different numbers and names, it offers fast and effective brute force attacks.

## Features

 - Multi-Website Brute Forcing:  FastBrute allows users to target multiple wordpress websites simultaneously, streamlining the brute force process and saving valuable time during security assessments.
 - Fast and Efficient: Leveraging the power of concurrent programming, FastBrute utilizes multi-threading to perform brute force attacks on multiple websites simultaneously. This efficient parallel processing significantly reduces the time required to complete the assessments.
  
 - Automatic Password Generation: FastBrute automatically generates a comprehensive list of passwords, combining common passwords with usernames extracted from the target websites. Additionally, it intelligently combines usernames with different numbers and variations to enhance the coverage of the brute force attack.
  
 - Easy to Use: Simple command-line interface with intuitive options for easy operation.
  
 - Detailed Reporting: After completing the brute force attacks, FastBrute provides detailed reports on the findings, including successful login attempts, failed attempts, and any potential security vulnerabilities discovered during the process. This comprehensive reporting enables users to analyze the results effectively and take appropriate remedial actions.

<br>

## How It Works

The tool leverages the XML-RPC of WordPress sites to perform brute force attacks. It first fetches user information from the target website(s) and then generates a list of potential username-password combinations. These combinations include default passwords, usernames combined with common words, and usernames combined with numbers, significantly expanding the attack surface. 

## Usage

To use FastBrute, simply provide a list of target websites and specify the desired number of threads for parallel processing. FastBrute will automatically initiate brute force attacks on the specified websites, combining usernames with different passwords and variations to maximize coverage and identify potential security weaknesses.
python CyberForceXBrute.py: This command invokes the FastBrute script using Python.

-l wordpress_sites.txt: Specifies the path to a text file containing a list of target websites. Each website URL should be listed on a separate line in the file.

-t 100: Sets the number of threads for parallel processing to 100. FastBrute will use 100 concurrent threads to perform brute force attacks on the target websites simultaneously.

By running this command, FastBrute will automatically initiate brute force attacks on the websites listed in wordpress_sites.txt, combining usernames with different passwords and variations to maximize coverage and identify potential security weaknesses.

  ```diff
git clone https://github.com/BharatCyberForce/CyberForceXBrute
```

```diff
cd CyberForceXBrute
```

```diff
pip3 install -r requirements.txt
```

```diff
python3 CyberForceXBrute.py -l list.txt -t 100
```
</br> </br>

# DISCLAIMER 
This tool is meant for educational purposes only. Unauthorized use of this tool on websites without proper authorization is illegal. Use responsibly and at your own risk.

</br> </br>
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7AB0A&width=435&lines=Developed+By+Indian+Cyber+Force)
