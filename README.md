# private-machines-ctf
Exploitable boxes that I built for fun and profit, the main goal was to learn about some vulnerabilities and how they work from inside.

## mKingdom
https://tryhackme.com/jr/mkingdom
<pre>
<details>
<summary>Click to reveal more about the machine</summary>
For this machine I developed a website that was broken on purpose, leading to remote code execution via command injection. Then, I set up privilege escalation with an insecure sudo configuration.
</details>
</pre>

## f4b
https://tryhackme.com/jr/f4b
<pre>
<details>
<summary>Click to reveal more about the machine</summary>
On this machine I focused on sensitive information disclosure vulnerabilities that lead to bruteforce on a login page. After that I configured the print page to be vulnerable to an LFI, thus getting the rsa key from one of the users. For the privesc, I set up a cron job that ran a script that could be edited by me, which every minute wrote a sentence inside another as another user.
</details>
</pre>

## alc47raz
https://tryhackme.com/jr/alc47raz
<pre>
<details>
<summary>Click to reveal more about the machine</summary>
On this machine, the goal was to learn more about how bash works and how to restrict many commands using rbash. I've set up a lab where you can try to escape and manage privilege escalation via a suid binary.</details>
</pre>

## moon
https://tryhackme.com/jr/moon
<pre>
<details>
<summary>Click to reveal more about the machine</summary>
In this one, I wrote a PHP script that is vulnerable to a log poisoining, but not the way you'd imagine. And then a very simple reverse challenge to privesc.</details>
</pre>
