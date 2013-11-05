A .NET wrapper for [tesseract-ocr](http://code.google.com/p/tesseract-ocr/).

## Warning - Prerelease software (alpha)

This is currently prerelease software as such the public API is subject to change.

## Dependencies

### Visual Studio 2012 x86 and x64 Runtimes 

Since tesseract and leptonica binaries are compiled with Visual Studio 2012 you'll need to ensure you have the 
Visual Studio 2012 Runtime installed. This can be found [here](http://www.microsoft.com/en-us/download/details.aspx?id=30679).

## Getting started quickly

Note: Compiling the project requires at least MS Visual Studio 11 Express for Desktop or SharpDevelop 4.4.

1. Fork this project (see: https://help.github.com/articles/fork-a-repo)
2. Ensure you have Visual Studio 2012 x86 & x64 runtimes installed (see note above).
2. Download language data files for tesseract 3.02 from http://code.google.com/p/tesseract-ocr/
3. Build BaseApiTester project
4. Copy language files into ``BaseApiTester\bin\[config]\tessdata``
5. Run BaseApiTester for example (work in progress)

## License

Copyright 2012 Charles Weld.

Licensed under the [Apache License, Version 2.0][apache2] (the "License"); you
may not use this software except in compliance with the License. You may obtain
a copy of the License at:

[http://www.apache.org/licenses/LICENSE-2.0][apache2]

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.

## Core Team

* [charlesw](https://github.com/charlesw) (Charles Weld)

## Contributors

A big thanks to GitHub and all of Tesseract's contributors:

* [jakesays](https://github.com/jakesays)
* [peters](https://github.com/peters)
* [nguyenq](https://github.com/nguyenq)
* [Sojin1989](https://github.com/Sojin1989)
* [jeschergui](https://github.com/jeschergui)

[apache2]: http://www.apache.org/licenses/LICENSE-2.0
