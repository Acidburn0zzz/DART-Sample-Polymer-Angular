DART-Sample Polymer + Angular
=============================

<strong>v0.3.0</strong>
Works now with Angular 0.10.0.<br>
I also removed "applyAuthorStyles => true" from polymer-elements.<br>
pub build works now.<br><br>
In "build/web" I added a little "webserver" script to serve the whole thing on :8000<br>
(Script needs python -m SimpleHTTPServer)<br><br>
<strong>I had to copy boot*.css from build/web/styles to build/web by hand!!!</strong><br>

To run the sample - go to <b>build/web/</b><br>
Run <b>./webserver</b><br>
In Chrome you should see <b>http://localhost:8000/index.html</b><br>

<strong>v0.2.0</strong>
Works with Angular (only in Dartium)<br>
event-handler is not supported anymore.

<strong>v0.1.2</strong>
event-handler added.
Now something like this works:
```html
    <event-handler>
        <hello-world></hello-world>
    </event-handler>
```

<strong>v1.1</strong>
Two components communicate with each other via EventBus.<br>
Another approach is to communicate via [shared Model][3].

###License###

    Copyright 2014 Michael Mitterer, IT-Consulting and Development Limited,
    Austrian Branch

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
    either express or implied. See the License for the specific language
    governing permissions and limitations under the License.

If this plugin is helpful for you - please [(Circle)](http://gplus.mikemitterer.at/) me
or visit my [website][99].

[1]: https://plus.google.com/u/0/+MikeMitterer/posts/2ztYDNPRi6K
[2]: https://rawgithub.com/MikeMitterer/DART-Sample-PolymerHelloWorld/master/build/index.html
[3]: https://github.com/sethladd/dart-example-two-components-one-model

[99]: http://www.mikemitterer.at/
