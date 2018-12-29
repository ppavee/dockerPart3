#Why to use Docker and what are the benefits?#

One of the major advantages of using Docker and why it’s usually related to the usage of cloud services,is the fact that
Docker is independent of the platform it is used on. Different operation systems – Windows, Mac, Linux etc. - or various
computer configurations, don’t have effects in the functionalities of Docker. The fact that Docker terminates the problem
‘it works on my computer’ describes well how useful this benefit is.
As I mentioned, the computer’s settings don’t affect Docker, but it applies also other way around. Because Docker doesn’t
affect the settings, it’s easy to try for a person who’s afraid that different processes could mess one’s computer. This
is part of the isolation of containers. It’s similar to the way virtual machines work. Isolation has also it’s importance
in the security of using Docker. If one container used in a multi-container application was compromised, others would still
be safe because the container’s aren’t aware of each other.
Application development is easy in Docker. When the needed base applications and files are included in the dockerfile, it’s
convenient to try out new configurations and to back up if needed.

A good example of what Docker is capable of by managing containers, is the YLE media downloader, which we were given as an
exercise. It’s based on Linux, but a person who operates on Windows is able to use it the same way, as long as the person
uses it through Docker. Although the previous example shows that Docker may be used with media files, the lack of build-in
graphical user interface shows that Docker isn’t capable of everything.
