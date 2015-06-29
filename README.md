# TelephoneNumber plugin for Phonegap #

The telephone number plugin allows you to retreive the devices phone numberfrom your PhoneGap application.

## Adding the Plugin to your project ##

Using this plugin requires [Apache Cordova 3.0+](https://cordova.apache.org).

1. To install the plugin, run `cordova plugin add https://github.com/surrealtechltd/TelephoneNumberPlugin.git`.

## Using the plugin ##

You create a new object that represents the plugin using cordova.require. Then you can call the 'get' method on that object providing a success callback which will be called with a result value that is the devices phone number.

<pre>
  /**
	* get the devices phone number.
    */
  get(success, failure)
</pre>

Sample use:

    TelephoneNumberPlugin.get(function(result) {
            console.log("result = " + result);
        }, function() {
            console.log("error");
        });
    

## RELEASE NOTES ##

### December 6, 2012 ###

* Initial release


## BUGS AND CONTRIBUTIONS ##


## LICENSE ##

This plugin is available under the MIT License (2008). 
The text of the MIT license is reproduced below. 

---

### The MIT License

Copyright (c) <2012> <Simon MacDonald., et. al., >

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.
 
