# Unity-QuickSheet


<p align="left">
    <a href="https://github.com/kimsama/Unity-QuickSheet/releases">
        <img src="https://img.shields.io/badge/pod-v.1.0.0-green.svg"
             alt="POD">
    </a>
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/license-MIT-orange.svg"
             alt="license">
    </a>
</p>

Unity-QuickSheet enables you to use google and excel spreadsheet data within Unity editor. With Unity-QuickSheet, you can retrieve data from a spreadsheet and save it as an asset file with a [ScriptableObject](http://docs.unity3d.com/ScriptReference/ScriptableObject.html) format even without writing single line of code.

<p align="center">
  <img src="./images/quicksheet01.png" width="80%" height=auto>
</p>

## Features

* **_Easy!_** No need to write any single line of code.
* **_Convenient!_** It can retrieve data from excel file. (both of xls and xlsx format are supported on Windows, only xls on OSX.)
* **_Flexible!_** It can also retrieve data from google spreadsheet.
* **_Fast!_** No need to write a parser to retrieve data, it automatically serializes retrieved data into Unity3D's [ScriptableObject](http://docs.unity3d.com/ScriptReference/ScriptableObject.html), the binary format and so it is fast than to use XML which is usually ASCII format.

Saying again, you don't need to write even single line of code to import data from a spreadsheet whatever Exced or Google spreadsheet.


## Documentaion

Documentation, located on GitBook site found on [here](https://kimsama.gitbooks.io/unity-quicksheet/content/).

#### Getting Started

See the following pages to quick start Unity-Quicksheet.

* [Excel Howto](https://kimsama.gitbooks.io/unity-quicksheet/content/excel-howto/)
* [Google Spreadsheet Howto](https://kimsama.gitbooks.io/unity-quicksheet/content/google-howto/)

#### FAQ

* See [FAQ](https://kimsama.gitbooks.io/unity-quicksheet/content/faq/) page for other information.

#### Release Note
* See the [Release](https://github.com/kimsama/Unity-QuickSheet/releases) page for change log.

#### Unity Forum
* You can also find it on the Unity forum page which can be found on [here](http://forum.unity3d.com/threads/released-unity-quicksheet.289146/).


## References

* [Unity Serialization](http://forum.unity3d.com/threads/155352-Serialization-Best-Practices-Megapost) on Unity's forum for details of serialization mechanism.
* [GDataDB](https://github.com/mausch/GDataDB) is used to retrieve data from Google Spreadsheet. Note that [GDataDB](https://github.com/mausch/GDataDB) is slightly modified to support *enum* type.
* [NPOI](https://npoi.codeplex.com/) is used to read xls and xlsx file.
* All "*.dll" files of Google Data SDK are available at [Google Data API SDK](https://code.google.com/p/google-gdata/downloads/detail?name=libgoogle-data-mono-2.1.0.0.tar.gz&can=2&q=)
* Newtonsoft.Json source code for net 2.0 is available at [here](https://github.com/JamesNK/Newtonsoft.Json)
* [Unity-GoogleData](https://github.com/kimsama/Unity-GoogleData), my previous effort to import a spreadsheet data to Unity.

## License

This code is distributed under the terms and conditions of the MIT license.

> Other code borrowed from [GDataDB](https://github.com/mausch/GDataDB) follow its the license.

Copyright (c) 2013 Kim, Hyoun Woo
