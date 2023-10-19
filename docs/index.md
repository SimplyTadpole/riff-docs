[![Contributors](https://img.shields.io/opencollective/all/riffcc?style=flat-square)](https://opencollective.com/riffcc)

# Welcome to the Riff.CC Wiki!
If you've stumbled into this page, congratulations - you have discovered and are hopefully interested in a platform for improving the world's access to free and open information!

Riff.CC is a non-profit project that aims to build an alternative to the current centralized server model - one that is decentralized, flexible, free and open-source, and powered by a low-cost content distribution system. Rather than hosting everything in a centralized server, Riff enables websites to host their files across various computers by virtue of letting users download copies of a website's data - such as images and uploaded files - on their personal drives, which then are forwarded to any device accessing a page that uses said data.

This process, made possible by the Interplanetary Filesystem (IPFS) protocol, helps future-proof websites and their contents by virtue of making it far less likely that their content becomes lost forever should the website ever shut down - all that is necessary is that at least one person still have the files and their according IPFS hash in a device with internet connection. With the increasing risks and cases of online data becoming lost media due to servers shutting down or being taken down, Riff.CC provides a solution that can easily make those issues a thing of the past.

Funding for the Riff.CC project is provided via [OpenCollective](https://opencollective.com/riffcc).


## How it works

When you upload a file to a server using Riff.CC, rather than providing an URL linking to a server's data - which will break should the server go down - it uses the aforementioned IPFS protocol to manage how the server accesses the file, by encurling it as a set of hashes called Content Identifier that points to the content on a decentralized network, as well as serving as a stamp of authenticity for the content. Furthermore, utilizing the same protocol, users can contribute to the server by downloading relevant data and media onto their own drives to decentralize the server's data storage.

As such, when the website requests a file - for example, a PNG image in a web page - if any server or device in the world connected to the internet has the appropriate file with a matching IPFS Content Identifier hash, the website will pull the relevant content from their drive and provide it to the user accessing the page that requested it, without depending on a domain name or other requirements and limitations in the current web format that makes data storage so fragile.

This greatly minimizes the costs of a server hosting the content, as well as the risk of said information being lost should the server go offline; because, if it does go offline, the data used in that server is still kept available by virtue of being hosted on others' spare hard drives, accessed through the Content Identifiers so long as at least one person still has the relevant file.

Websites running on the Riff.CC platform as well as users participating in it can also federate with each other to co-host each other's contents, similar to platforms utilizing protocols such as ActivityPub; however, unlike those, federation in Riff.CC is opt-in rather than opt-out in order to reduce the risks of servers and users being exposed to harmful and extreme content such as CSAM. In the event that they do get exposed to it, the IPFS protocol also has a "bad bits" blocking feature, which lets users report a Content Identifier hash as being problematic or illegal.


## How to run it

There are two different platforms Riff.CC can be hosted on - **Orbiter**, which utilizes OrbitDB as its backend and is used to host the main Riff.CC instance; and **CeramicRiff**, which utilizes Ceramic as its backend. Both have different setup procedures, but the process of running them is largely similar.

Refer to the below shortcuts on relevant pages for instructions:

* Installation
    - [Install using Orbiter](https://github.com/riffcc/orbiter)
    - [Install using CeramicRiff](https://github.com/riffcc/ceramic-riff-web)
* Running and Maintaining

## Credits
Authored by [@Zorlin](https://github.com/Zorlin), [@julienmalard](https://github.com/julienmalard), [@en0c-026](https://github.com/en0c-026), [@SimplyTadpole](https://github.com/SimplyTadpole) and the Riff.CC Project.

## Sponsors
Thank you to our sponsors, who have generously provided funding for the development of the Riff.CC Project:

* [Money Every 3 Days](http://moneyevery3days.com/)
