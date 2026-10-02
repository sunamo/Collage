## Short description

Fork aplikace Collage od Piotra Ludwiczuka: tvoří koláž z množiny obrázků (knihovna `Collage.Engine`, konzolová a WinForms aplikace). Engine byl v tomto forku převeden na SDK projekt .NET 9 s `SunamoExceptions`, konzolová a WinForms část zůstaly na .NET 4.5.

## Collage ##

Simple application that creates collage of a given set of images.

.NET 4.5 (C#)

![Collage - windows forms app](http://if.pw.edu.pl/~ludwik/images/collage3.jpg)

### Console application ###

`mono collage.exe -i /home/piotr/Pictures/ -o /home/piotr/ -th=10 -tw=10 -r=10 -c=10 -rf`

### Windows forms application ###

![Collage on Windows](http://if.pw.edu.pl/~ludwik/images/collage_win2.png)
