---
layout: post
title: My days at Lakademy
tags: KDE free-software
---

Hello, everyone! :)

<br>
Last Thursday(12/10/2018) happened the 6th edition of the Lakademy meet up and I'm more than grateful to say that I participated. It was my first and I really hope I participate of many more.
Me and six other friends from Niterói, Rio de Janeiro went to Florianópolis, Santa Catarina, where the event took place. At first I was nervous for being a newbie but I felt instantaneously more comfortable when just arrived at UFSC (Universidade Federal de Santa Catarina), where we were gathering to work together. There I met so many awesome people! I didn't even know people could be that awesome. They were so receptive that the will to contribute with the community and be around them could only increase. Now I'll try to talk about what happened in each of the days we spent there.

<br>
## Day 1:

<br>
The flight was quick, about an hour and a half. We arrived left the luggage at the hostel and went to UFSC. I was kinda nervous, at this point, from KDE, I only knew Tomaz Canabrava, Sandro Andrade and Chris Rizzitello, from telegram chats and video calls only. So that was it, we entered the auditorium and they were astonishingly receptive, asking us to presentate ourselves and thanking us for comming. We were told to work in whatever we wanted to. There were coffee. There were snacks. Good to go.
I decided to keep working on this lovely project I was working before Lakademy called Minuet, It was created by Sandro Andrade. Since the beginning of the semester(August/2018) I've been working on a new feature that implements singing exercises by recognizing the notes an user sings to the microphone. I spent about two months on research of how could I detect the frequencies from a sound. At the end of this process I knew I had to use an algorithm called FFT (Fast Fourier Transform) and a bit of how it works. So in the beginning of the first day of Lakademy I spent looking for some C++ implementations of FFT. Found an awesome one called FFTW (<a href="http://www.fftw.org/" target="_blank">Fastest Fourier Transform in the West<a>) it works and is available in the majority of package repos. So my main goal at the first day was to recognize the main frequency of a generated sine wave. I was struggling at first with C++ and Qt, FFT works in the complex domain, so I had to figure out how to work with FFTW, generate valid input and interpret the output. At the end of the day I managed to do the job! My program could receive the samples of a sine wave and tell what was the frequency! I could call it a day. At night we went to an arabic food restaurant and I think the owner never seen that many people in there, he seemed so happy.

<br>
## Day 2:

<br>
We had breakfast at the hostel and headed to UFSC. This time I was much more confident in interacting with everyone. When I was recalling what I had form last day I realized my implementation had some flaws with edge cases, therefore, was not working properly. At first I was struggling in figuring out what the problems exactily were. It was when a very nice guy called Dórian Langbeck got intersted with what I was doing and did an amazing job helping me to debug everything. ~~He~~We created a quick implementation using python and a jupyter notebook with nice plots and it was very helpful for me to better understand the problem. After that all I had to do was to translate all of our conclusions back to C++. Said and done. Now it was working nicely with every input possible. This day may not seem that much productive. I really could not say "Oh my this was the most productive day ever" but I learned a lot about what I was doing and from Dórian and the other guys that were helping in the process. At night we spent a lot of time deciding what we were going to do. We ended up ordering some pizza and beer. I spent the rest of the night in a conversation with Pedro Duarte, Fred Guimarães, Bianca Oliveira and Dórian about free software, life and everything, if I already was in love with the free software world now I was a hundred times more, I realized how little I knew and how amazing this sense of community is. Such a memorable exchange of ideas. It went well with the pizza (and the beer!)

<br>
## Day 3

<br>
TL;DR: This was the day I fell in love with KDE community


