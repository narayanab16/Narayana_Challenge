# Comcast Solution Challenge
# Problem1: IaaC to render static html content on the browser with http/https enabled
# Solution1 Analysis:  
      1. Virtual Machine required with some hardware capacity say 4 gb ram, OS installed either RHEL 7.x, 8.x, Internet connection, Root or sudo root user and access details
      2. To fullfil problem statement required following softwares I have selected here apache web server for the solution software
         2.1 Chose Apache Web Server, OpenSSL, Self-Signed or with CA Certificate chains 
      3. Used apache VirtualHost, Directory, mod_ssl  etc directives to host static web content.
      4. Here i have used manual way
      5. i have provided steps to complete the solution # see Apache_SSL.txt
      6. I know Linux admin self networking LAN setup, port forward at kernel level and DNS setp, NTP setup, Firewall at my home
      6. We can use Terraform or CloudFormation to do those activities.
      
# Problem2: Credit Card Validation using either python/go
# Solution2 Analysis:
      1. Python interpreter required to solve the puzzle : i chose online https://www.programiz.com/python-programming/online-compiler/
      2. There were a lot of conditions to be satisfied for a given input credit card.
      3. I have decided to use some regular expression pattern to solve the challenge. i took sample from  pattern usage     https://docs.oracle.com/javase/7/docs/api/java/util/regex/Pattern.html, https://docs.python.org/3/library/re.html
      4. I used python "re" module to solve the puzzle
      5. CreditCardValidation.py
