NibWrapper
==========

Nesting NIBs ni other NIBs has never been that easy.

# How To

## 1. Nested Nib

1. Create a UIView subclass with a xib file with the same name as the class.
2. Customize the xib file and the class as you want.

![](https://raw.githubusercontent.com/mobilejazz/NibWrapper/master/README-images/Nib2.png)
![](https://raw.githubusercontent.com/mobilejazz/NibWrapper/master/README-images/Nib2-conf.png)


## 2. Parent Nib

1. In your parent nib, add a UIView and setup at as a `UINibWrapper` class. 

2. In the "User Defined Runtime Attributes" add an entry for the key *className* of type string and add the name of your custom view.

![](https://raw.githubusercontent.com/mobilejazz/NibWrapper/master/README-images/Nib1.png)
![](https://raw.githubusercontent.com/mobilejazz/NibWrapper/master/README-images/Nib1-conf.png)


## 3. Go!

Run your project and you are done!

![](https://raw.githubusercontent.com/mobilejazz/NibWrapper/master/README-images/Result.png)



