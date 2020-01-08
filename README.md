This is a VM image that has all of the dependencies you need for class installed. Once you have cloned this repository
you can get to the VM by running the following:


```
vagrant up # This will create and provision the VM if not already done.
vagrant ssh # This will log you into the VM
```

You can subsequently suspend the VM using `vagrant suspend` and halt the VM either by running `sudo shutdown -h now`
inside the VM or calling `vagrant halt` on the outside.

Finally you can delete the VM by calling `vagrant destroy`, however note that **this will delete all content in the VM**
and is probably not what you want to do.
