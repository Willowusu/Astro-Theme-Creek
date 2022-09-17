---
title: "Have you been compromised?"
description: "An article taht helps you to detect if you have been compromised, how to rectify it, adn how to prevent it"
pubDate: "2020-03-10"
hero: "https://cdn-images-1.medium.com/max/2000/1*JmPGvRv5BywPay2jKc93gw@2x.jpeg"
tags: ["security"]
layout: "../../layouts/BlogPostLayout.astro"
---

## Have you been compromised?

![](https://cdn-images-1.medium.com/max/2000/1*JmPGvRv5BywPay2jKc93gw@2x.jpeg)

In the recent iOS 14 update Apple added a feature called Security Recommendations that has really been an eye-opener. It tells you if you’re reusing your saved passwords in the keychain on other sites, whether it’s too weak and a feature that can alert you if your passwords appear in known data leaks. Google also has a similar feature in Chrome(Google’s “default” password manager) called Password Checkup that has the same functions except alerting you if your password has appeared in a data leak.

After visiting this on my iPhone I realized that most of my passwords had been found in a data leak. **I had been compromised.** For someone who is as security conscious as myself I had failed in “Cybersecurity 101”. I had reused the same password on other sites. And even though those sites hadn’t been breached, it would have been easy for an attacker to hack and gain sensitive information about me on multiple sites if they got their hands on my compromised password and username.

Someone might ask: “Why not use the password suggested by either the browser or app you’re using?” The reason I decide my passwords on my own is because I hop between different operating systems from time to to time and it is quite a bother updating a 16 character length password suggested by the iCloud Keychain in my Chrome manager for example. The best solution I have found so far is using a cross platform password manager. But that will be talked about in the next article.

This article will show you how to find the Security Recommendations and Password Checkup feature on both iOS and Android platforms respectively. And what to do if you’ve reused passwords, employed weak password techniques or you have been compromised.

## On iOS Devices

- Go to Settings

- Scroll down and tap on Passwords

- Tap on Security Recommendations

- If deactivated, activate “Detect Compromised Passwords”

This will tell you all you need to know about the passwords saved in the keychain. Take every prompt seriously.

## For Android or Chrome Users

- Tap on your Chrome browser

- Tap on Settings

- Tap on Passwords

- Tap on [passwords.google.com](http://passwords.google.com)

- Tap on “Go to Password Checkup”

An alternative way is also going straight to [passwords.google.com](http://passwords.google.com) on your device if you have passwords saved in Chrome.

## What next?

If you find out you have been compromised, your password is being reused on multiple sites or you have a weak password;

- Change the password used on that site immediately.

- Use a password manager or any app that can generate random strong passwords. I would recommend the in-house managers of your device (Chrome and iCloud Keychain).

- If it’s a site you hardly use and the option is available, delete your account on that site.

- If you do not trust a password manager and you would like to generate your own password use a pass-phrase instead. Change a few alphabets to numbers and make sure it’s at least 12 characters. They are more difficult to be hacked.(eg. Wearyo5rmaskPl3ase)

And remember: **never, EVER, use the same password twice.**

Bottom line is, you can never be too sure about whether you will be breached or not but it’s better to be safe than sorry.
