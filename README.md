angular-zxcvbn
==============

Usage
-----

Install with bower:

    bower install zxcvbn angular-zxcvbn --save

Add to your HTML files:

    <script src='/bower_components/zxcvbn/zxcvbn-async.js'></script>
    <script src='/bower_components/angular-zxcvbn/angular-zxcvbn.js'></script>

Now, inject to your application:

    angular.module('myApp', ['angular-zxcvbn']);

Ready to use in your views!:

`index.html:`

```html
Time to crack your password <zxcvbn password='passwordVar'></zxcvbn>
```

There's another input variable available called `extra` where you can put an array with other strings the user has inputted like name, username or email, that way `zxcvbn` gets a better time to crack estimate.

Author
------
© 2014, Jose Luis Rivas `<me@ghostbar.co>`. 

License
-------
The files are licensed under the MIT terms.