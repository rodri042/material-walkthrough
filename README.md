# material-walkthrough
A material tour (eg Inbox from Google), for your site enhancing the UX.

## Features
* Material Design - Have a Material look, based on the tour presented by Google Inbox.
* Customizable - Change the text and colors easily.
* Responsive - Resize the screen and continue enjoying your Walkthrough.
* Simple - With a few lines of code you will got a Walkthrough
* Compatible - Google Chrome 52.0; Firefox 48.0.2; Microsoft Edge 38.14393.0.0.
* Made with love - Much love and a few nights without studying to develop this plugin with much love 

## 1. Getting Started
Load jQuery() and include Material-Walkthrough plugin files
```html
<!-- Basic stylesheet -->
<link rel="stylesheet" href="material-walkthrough/material.walkthrough.css">

<!-- Include js plugin -->
<script src="material-walkthrough/material.walkthrough.js"></script>
```

## 2. Set up your HTML
You don't need any special markup. All you need is to add an `id` atributte to an HTML element. 
```html
<a id="step1">Try Now!</a>
```

## 3. Call the plugin
Now call the Material Walkthrough initializer function and your walkthrough is ready.
```javascript
$.walk([
        {
            selector: '#step1',
            text: 'Here you can begin the walk!',
            color: 'red',
            acceptText: 'OK'
        }
]);
```
# License
  Copyright 2017 Esset Software LTD.
 
  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this files except in compliance with the License.
  You may obtain a copy of the License at
 
  http://www.apache.org/licenses/LICENSE-2.0
 
  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.