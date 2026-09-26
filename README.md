\# AYRADE Web Server



\## Project Overview



This project was developed as part of the AYRADE technical recruitment test.



The objective was to deploy a web server on a Linux virtual machine using AlmaLinux and Apache HTTP Server, then make the website accessible directly from the Internet without using Ngrok or any tunneling service.



\## Technologies Used



\- VirtualBox

\- AlmaLinux

\- Apache HTTP Server

\- HTML

\- Linux Firewall

\- ZTE Router

\- Port Forwarding

\- Git

\- GitHub



\## Network Architecture



```text

Internet

     |

     v

Public IP :80

     |

     v

ZTE Router

192.168.1.1

     |

     | TCP Port 80

     v

AlmaLinux VM

192.168.1.12

     |

     v

Apache HTTP Server

Port 80

     |

     v
 
/var/www/html/index.html

     |

     v

Welcome AYRADE

