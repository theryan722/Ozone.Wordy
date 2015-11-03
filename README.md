# Ozone.Wordy
![License](https://img.shields.io/badge/license-Apache-blue.svg)
![Release](https://img.shields.io/badge/release-v1.0.0-blue.svg)
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)
![Current Release](https://img.shields.io/badge/current%20release-Stable-brightgreen.svg)
![Current Build](https://img.shields.io/badge/current%20build-Stable-brightgreen.svg)

Procedural Text and Word Generator

###What is it?
Ozone.Wordy is a procedural word and text generator for .Net

###Binaries
You can download the library from the [releases](https://github.com/theryan722/Ozone.Wordy/releases/) page.

###Examples
Here is an example of the UpdateString() method:
```c#
String example = "The {noun} wanted to {verb} with the {adjective} toy."
example = Ozone.Wordy.Core.UpdateString(example);
```
This could output:
> The truck wanted to play with the shiny toy.

It could be anything however, since it is random.

Or you could simply want to get a random word such as
```c#
String example1 = Ozone.Wordy.Core.GetRandom(Adverb);
String example2 = Ozone.Wordy.Core.GetRandom(Preposition);
```

###Future Plans
I have plans to implement more specific text generation, i.e. being able to specify an animal, or building, or location, etc.

###License
Copyright 2015 Ryan O'Day

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
