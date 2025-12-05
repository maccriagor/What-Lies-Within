# Challenge Name: What Lies Within
**Category:** Forensics  
**Platform:** picoCTF 2019  
**Points:** no info.

## Description
There's something in the building. Can you retrieve the flag?
Link the the building.png file : https://challenge-files.picoctf.net/c_fickle_tempest/c0eec6af0f04316e2bdc4a9f095afd0e2d0121f5e543dbc4a65bb0038d72a993/buildings.png.
## Challenge Hints
There is data encoded somewhere... there might be an online decoder.
## Personal Hints
1. This challenge is really short so all i have gotta say is that since its a .png file, you can check its rgba content with either the command zsteg or the following online decoding tool : 
## Analysis
- The challenge gives you one file :
1. Buidling.png content :
   
   <a href="https://ibb.co/7tQGbD0M"><img src="https://i.ibb.co/Qvk6XVxS/buildings.png" alt="buildings" border="0"></a>

The challenge's fundamental is similar to that of RED challenge , its just a different image with lesser hints but very similar ( and short ) solution, heck even easier than RED .
You can check out RED challenge right here : https://play.picoctf.org/practice/challenge/460?category=4&page=1.
## Solution
Step-by-step explanation:

Visit Aperisolve steganography tool : https://www.aperisolve.com/

* This was the online decoder that i used back when i was on RED challenge, later on i found out that the picoCTF webshell does contain the zsteg command to do similar task.
1. Since this is a .png file, zsteg can be used to check its rgba content.
   
   <a href="https://imgbb.com/"><img src="https://i.ibb.co/k6WMFsVc/Screenshot-2025-12-05-112808.png" alt="Screenshot-2025-12-05-112808" border="0"></a>
   
## Result
The flag for this challenge is picoCTF{h1d1ng_1n_th3_b1t5}.
