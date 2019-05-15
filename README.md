xAPIVerbs
=========

ADL Experience API Verbs  
  
The Javascript file attaches an ADL object to the window allowing scripts to access the list of ADL Verbs, 
such as experienced, passed, imported and launched. This makes it easy to use the ADL Verbs, just include this 
file in your html and access it using json notation. See usage and examples below.

## Installation

Either clone:

`git clone https://github.com/adlnet/xAPIVerbs`

or 

[Download directly](https://github.com/adlnet/xAPIVerbs/archive/master.zip)


## Usage


Include the script in your html 
```html
<script type="text/javascript" src="./js/verbs.js"></script>
```
  
Reference the verbs in javascript using json notation
```javascript
var statement = {
  "actor" : {"mbox":"mailto:tom@example.com"},
  "verb" : ADL.verbs.registered,
  "object" : {"id":"http://adlnet.gov/expapi/activities/using-xapi-verbs"}
};
```

## Examples

see:
- https://github.com/adlnet/LRSGame
  - [index.html](https://github.com/adlnet/LRSGame/blob/master/index.html)
  - [/js/Game.js](https://github.com/adlnet/LRSGame/blob/master/js/Game.js)
- https://github.com/adlnet/LRSGameDashboard
  - [index.html](https://github.com/adlnet/LRSGameDashboard/blob/master/index.html)
  - [/js/stats.js](https://github.com/adlnet/LRSGameDashboard/blob/master/js/stats.js)

#### Languages  
- fr-FR  France French
- de-DE  Germany German
- en-US  United States English
- es-ES  Spain Spanish
- it-IT  Italy Italian
  
## Contributing to the Project
If you want to help make this better, please feel free to fork and make edits. Submit a pull request back to 
this project and we will review and pull it in.  

If you natively speak a language that isn't in the display object of a verb, fork this project and add it. 
If you aren't comfortable with using GitHub, you can [add an issue](https://github.com/adlnet/xAPIVerbs/issues/new) 
and let us know what language code and the translation for each verb.

## License
   Copyright &copy;2016 Advanced Distributed Learning

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
