[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/287f55bc8bb5d2bda275b4e2f565405f "githalytics.com")](http://githalytics.com/BelfordZ/BoilDatJs)
<b>What does it do? </b>
I'm sick of writing boiler plate js and index.html, linking all the scripts etc. Further, I'm sick of having giant JS files, and prefer C-like 'file per class'. So I made this shitty bash script to do it for me, and hopefully over time it will do a lot more.

<b>It's simple as it gets</b>
Just type this into your terminal:
<ul>
<li>'mkdir BoilDatJs'</li>
<li>'cd BoilDatJs'</li>
<li>'git clone git@github.com:BelfordZ/BoilDatJs.git'</li>
<li>'install'</li>
</ul>

There ya' go. Next time you are starting a new project make your directory and type:
<ul>
<li>'boiler' [any number of classes to make]</li>
</ul>

<b> Example </b>
boiler myClass1 myClass2 myClass3
outputs files: index.html, myClass1 myClass2 myClass3
index has the linked scripts, js file functions are properly named