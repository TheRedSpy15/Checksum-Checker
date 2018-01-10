# Checkersum-Checker
A checksum checker made in Java using JavaFX, that supports a range of hashes.

**SUPPORTS**
* MD5
* SHA-1
* SHA-224
* SHA-256
* SHA-384
* SHA-512


<a class="github-button" href="https://github.com/TheRedSpy15/Checkersum-Checker/archive/master.zip" data-icon="octicon-cloud-download" data-size="large" aria-label="Download TheRedSpy15/Checkersum-Checker on GitHub">Download</a>

[![Checksum_Checker_Screen_Shot_UPDATED.jpg](https://s13.postimg.org/6mv5apmpj/Checksum_Checker_Screen_Shot_UPDATED.jpg)](https://postimg.org/image/4ias9ml2r/)


## What's it used for?

You know when you try to download a file off the internet, or have a super important email and want to make sure nothing happened to it along the way to your router, or even tampered with while you were away? Well, checksums are basically a fingerprint for a file on your computer, and is extremely unique (not %100 percent however) to your specific file. Attempting to keep the same fingerprint for a file after it was modified, is EXTREMELY difficult.

SO... when you download launchcodes.exe from a website, look for a hash or something that says something like: MD5, SHA-1, or SHA-256. Those are hashes used to add a fingerprint to your file. Use those to compare against the copy locally on your computer, to make sure nothing bad happened to them.

## What's it NOT used for?

It will not protect you from viruses.

At-least, not when the original file was one. It will protect you from viruses/malware, when the virus/malware was added to the file in transit, or while you were away (assuming you know the orginal checksum associated with the file before hand).

### Java is required!
