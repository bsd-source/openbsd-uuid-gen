### **Generate Random UUID on OpenBSD**

**Type of UUIDs**

UUIDs are defined in [RFC 4122](https://tools.ietf.org/html/rfc4122). There are different versions using different ways to generate UUIDs for different purposes. UUID version 4 is the easiest one to create and doesn’t require any user input or preexisting data like a MAC address.


**The Script**

The shell script generates random numbers and sets the required bits according to [RFC 4122](https://tools.ietf.org/html/rfc4122), then prints a version 4 UUID in the common format as string to stdout.

>Example output:
>c473841c-5077-4d01-b8ed-840f8cce9d1


**Acknowledgements**

This script was found on https://www.bsdhowto.ch and created by [Bruno Flückiger](https://runbsd.info/people/bflueckiger.html) for OpenBSD.
