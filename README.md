# sql2
I'm trying to use MySqlSwiftNative from Cocoapods to make a connection from my iphone app to MySql server but after install Swift Package Manager and MySqlSwiftNative, I CAN NOT import (or load) the class MySqlSwiftNative or MySqlDrive into my ViewController. Can anyone help please.
Below are what I did:
openned new project in Xcode, named sql2
exit Xcode, go to Terminal
cd ~/sql2/
>swift package init --type library
>swift package generate-xcodeproj
(for this sql2 version, I did not edit the Package.swift file to include any dependency path)
>pod init
(modify Podfile to include 'MySqlSwiftNative', '~> 1.0.10'
>pod install
That's it.
and I can not import (or Xcode can not locate) whether MySqlSwiftNative or MySql or MySqlDriver class. What do I have to do?
