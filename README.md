# Exploit For Spring4Shell In Ruby 

# Spring4Shell | Spring Core RCE | CVE-2022-22965
This is a dockerized application that is vulnerable to the Spring4Shell vulnerability (CVE-2022-22965). 

# How To Reproduce 
docker run -d -p 8082:8080 --name springrce -it vulfocus/spring-core-rce-2022-03-29

# Usage 
`ruby CVE-2022-22965.rb target_url`


# p0c

https://user-images.githubusercontent.com/24976957/163680653-fb3d4f3e-8b3f-4874-b1a7-8d2bd3436242.mov

