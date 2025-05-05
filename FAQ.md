
### Why are your addons so ugly?

I am not a designer and i find CSS to be dedious/boring to a certain degree.
That said, anyone is welcome to make PRs.

### Why are the issue pages in your repositories disabled? 

At the moment i find it easier to manage if i have all issues in one place. 
Should the number of issues, collaboraters or something else change i might reconsider this.

### Can i use your stuff? 

Sure, go ahead. If you plan an releasing something build on or from it into the public domain 
it would be nice if you left a mention somewhere. Otherwise, have fun.   

### How do i know the stuff i install on AMO is the same as what is hosted here?

1. Download the addon xpi file on AMO
2. Change the extension to ".zip"
3. Extract it

It will include the same files you'll find in the repositories aside from an extra folder that holds some signature information added by mozilla which allows the browser to verify that this addon passed the AMO review and can be persistently installed into the stable version of firefox. 

### Can you make an addon for me?

Maybe ... it depends ... i like to create stuff that has the potential to be useful for more then just one person.
But if i am in a good mood and you have a good reason and i estimate the effort to not be unreasonable ... i might help out anyways. 
So, just open an issue and provide as much details about your problem as possible and see what happens. 

### Why dont your addons work on some mozilla sites?

There are some restricted domains, where addons are not allowed to be run, without making some very specific changes, so this isn't something i intentionally choose, but rather something that mozilla did to add additional protection for its users. 

### Which commit corresponds to a version hosted on https://addons.mozilla.org? 

The AMO version is linked with the `version` attribute inside the `manifest.json` file.
If you are looking for the code of a specific version, go to the commit, where the `manifest.json`'s `version` attribute is changed to correspond with the version you are interested in.

### Why dont you host the xpi files on github?

The current async nature of the AMO API makes it difficult to automate getting the signed XPI back with github actions, so if i wanted to have these here, i'd have to manually transfer them ... which i'd rather not, at least at the moment.

### Why do you delete older issues?

It helps me to better focused on the still relevant ones and i dont see that much value in retaining them.
In many cases those might even contain outdated or misleading information which users might even get confused by.

### How to exchange sensitive information? 

First open an issue so i can get back to you, then send the sensitive information 
to the w7d7289je (AT) mozmail (DOT) com 
Use the same issue title as the subject in the mail, so i'll be able to match them up. 

### Why is addon X not hosted on AMO?

The two main reason could be

1. The addon does not fully comply with the AMO's TOS and is therefor simply not hostable there.
2. The addon was on AMO for a while but it did not gather enough interest that i thought it reasonable to keep maintaince up.
