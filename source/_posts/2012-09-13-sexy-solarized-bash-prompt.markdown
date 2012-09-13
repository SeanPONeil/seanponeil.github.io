---
layout: post
title: "Sexy Solarized Bash Prompt"
date: 2012-09-13 16:11
comments: true
categories: 
---

As you can already tell from this site, I have a love affair with
[Solarized](http://ethanschoonover.com/solarized), and I will defend The
Perfect Color Scheme until The More Perfect Color Scheme comes out. In
the mean time, however, I've been working on making my shell more
Solarized friendly. Enter Sexy Bash Prompt: 

{% img /images/sexybashprompt.png %}

For anyone who finds themselves typing pwd or git branch a little bit
too much, this bash customization is a lifesaver. The only caveat: the
color scheme is not The Perfect Color Scheme. Enter Sexy Solarized Bash
Prompt:

{% gist 3717199 %} 

The entire color scheme is present for both 256 color mode and 16 color
mode. The colors that are actually used in the new bash prompt can be
changed or rearranged at the last line of the file. To use it, copy the
code above into ~/.bash_prompt and source it. The final result will look
something like this:

{% img /images/sexysolarized.png %}
