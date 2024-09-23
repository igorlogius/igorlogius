
### Why are your addons so ugly?

I am not a designer and i find CSS to be dedious/boring to a certain degree.
That said, anyone is welcome to make PRs and improvment suggestions.

### Why are the issue pages in your repositories disabled? 

At the moment i find it easier when everything is in one place. 
Should the number of collaboraters increases or something else change i might change this on a per repository basis. 

### Can i use your stuff? 

Sure, go ahead. If you plan an releasing something build with/on it into the public domain, 
it would be nice if you left a mention somewhere. Otherwise, have fun.   

### How do i know the stuff i install on AMO is the same as what is hosted here?

1. Download the addon xpi file
2. Change the extension to ".zip"
3. Extract it

It will include the same files you'll find in the repositories aside from an extra folder that holds some signature information added by mozilla which allows the browser to verify that this addon passed the AMO review and can be persistently installed into the stable version of firefox. 

### Can you make an addon for me?

Maybe ... it depends ... i like to create stuff that has the potential to be useful for more then just one person.
But if i am in a good mood and you have a good reason and the effort is not unreasonable ... i might help out anyway. 
So, just open an issue and provide as much details about your problem as possible and see what happens. 

### Why dont your addons work on some mozilla sites?

There are some restricted domains, where addons are not allowed to be run, without making some very specific changes, so this isn't something i intentionally choose, but rather something that mozilla did to add additional protection for its users. 

### Which commit corresponds to a version hosted on https://addons.mozilla.org? 

The AMO version is linked with the `version` attribute inside the `manifest.json` file.
If you are looking for the code of a specific version, go to the commit, where the `manifest.json`'s `version` attribute is changed to correspond with the Version you are interested in.

### Why dont you host the xpi files on github?

The current async nature of the AMO API makes it difficult to automate getting the signed XPI back with github actions, so if i wanted to have these here, i'd have to manually transfer them ... which i'd rather not, at least at the moment.

### Why do you delete old issues?

I generally like to remove old resolved issues after a certain time cause i dont see much value in retaining them. 
If something becomes relevant it's best to open a new issue.  

### How to share sensitive information? 

First open an issue so i can get back to you, then send the sensitive information 
to the [support email](mailto:w7d7289je@mozmail.com) 
Use the same issue title as the subject in the mail, so i'll be able to match them up. 

