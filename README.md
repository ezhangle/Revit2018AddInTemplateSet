# Revit 2018 Add-In Template Set

This is a set of Visual Studio 2017 templates for creating Revit 2018 add-in projects.

© Andrey Bushman, 2017, [blog in Russian](https://revit-addins.blogspot.ru/2017/02/revit-visual-studio.html)

**WARNING!**

After the templates installing you are to delete the directories:

 * `%AppData%\Microsoft\VisualStudio\15.*\ItemTemplatesCache`
 * `%AppData%\Microsoft\VisualStudio\15.*\ProjectTemplatesCache`

 Visual Studio 2017 recreates they when you will create new project or add new item to a project.

It contains:

- Revit 2018 External Application (C# Project Template)
- Revit 2018 External DBApplication (C# Project Template)
- Revit 2018 Class Library (C# Project Template)
- Revit 2018 External Command (C# Item Template)
- Revit 2018 External Command Availability (C# Item Template)
- Revit 2018 Updater (C# Item Template)
- Revit 2018 New Class (C# Item Template)

The `Revit 2018 External Application` contains the special additional configuration &ndash; `Debug via Revit Add-In Manager`.
It allows to you edit and debug your commands code without Revit restarting.

Templates of all projects contain the search engine for searching of the absent assemblies.
You can use the `AssemblyResolves.xml` configuration file for managing of where is located your absent assemblies.

The projects created on the base of these templates can be checked by [PVS-Studio](http://www.viva64.com/en/pvs-studio/) static code analyzer.

Also it contains configurator which can configure the settings
of these templates for you and install them on your local
machine from their code sources.

Join the [gitter Revit2017AddInTemplateSet chat](https://gitter.im/Revit2017AddInTemplateSet/Lobby).

These old video lessons show how to install and how to work with these templates:

- #001. [Download and install the templates](https://www.youtube.com/watch?v=SYm-yxQ9jFk&t=1s)
- #002. [Create new project](https://www.youtube.com/watch?v=TU5HoTxpgbk&t=5s)
- #003. [Add new command](https://www.youtube.com/watch?v=mtw8PAf5eus&t=2s)
- #004. [Link the command with the command availability](https://www.youtube.com/watch?v=-_79p0CnKJY&t=8s)
- #005. [Add ribbon tabs and panels](https://www.youtube.com/watch?v=wlskC5PTmH8&t=4s)
- #006. [Template resources using](https://www.youtube.com/watch?v=_aQ30GHl3as&t=1s)
- #007. [Multilanguage add-ins creating](https://www.youtube.com/watch?v=abxy-Ynff3w)
- #008. [Debugging using Add-In Manager](https://www.youtube.com/watch?v=QFFwG6rz0gc)
