JSONToObjC
==========

JSON to ObjC model generation

Convert your JSON into Objective C model files.

Steps:

1.Open project in Xcode and paste your JSON into the following file
/Classes/json/json.json

2.Enter the name with which you want the files to be generated, in JSONObjectToObjCModelAppDelegate.m 
/#define CLASSNAME @"yourFileName" //e.g. UserModel

3.And then perform a 'Build and Run'.

Check console output to see the path of generated Objective C files.(.h and .m)
