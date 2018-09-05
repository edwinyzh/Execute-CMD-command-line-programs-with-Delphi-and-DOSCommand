![](media/85162b41618a63d54342d366f4635ac0.png)

**Execute CMD command-line programs with Delphi and DOSCommand.**

**Background**

When requiring a command –line program in your Application, setting up
‘createprocess ‘ and pipes is not that difficult. But it would be important to
multithread your code so that your application is not stalled while your
command-line application is running.

Save yourself the trouble as it is easier to use ‘DosCommand’. Straight out, it
is not a simple to use component as it looks?

**Free Component**

The TurboPack DOSCommand [Component Information in
Github](https://github.com/TurboPack/DosCommand) indicates the following:-

This Component lets you execute a Dos program (exe, com or batch) and catch the
output in order to put it in a memo. It states that the result should come back
line by line.

You can download the Component from Github or through the GETIT Manager.

Limited examples can be found in the source Header and are a little outdated and
lacking explanation.

**Example App**

Here is an Example App set up with code that calls various exe(s) such as
ipconfig etc. The code is available to download.

![](media/9f92a195f1a08e34b01910b8dd1ae522.gif)

**Making DosCommand Work**

My blog covers the full detail on this component. Click on the Url to get the full story.

[delphi-command-line-programs-with-doscommand](https://bayeseanblog.com/blog/delphi-command-line-programs-with-doscommand/22)


Happy Coding
