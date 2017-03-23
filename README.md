# c3e-support
Guides and forum for http://c3e.thegeez.net

# c3e is a beta release!
All data in c3e is public! Data storage is not guaranteed and data may be deleted at any time!

# Run the sample figwheel project
1. Goto http://c3e.thegeez.net, a user account and a project will be created for you
2. Goto "Dashboard" via the button on the left hand side. On the "Dashboard" click "Create new project from .zip file" with this url: https://github.com/thegeez/c3e-figwheel-example-project/archive/master.zip (The example project code is at https://github.com/thegeez/c3e-figwheel-example-project).
3. Download "c3e-file-sink" from https://github.com/thegeez/c3e-support/releases/download/v0.0.1/c3e-file-sink-0-0-1-prod-standalone.jar to a location/server. With "c3e-file-sink" the files you are at editing within c3e will also be updated in the file system location of your choice.
4. Use the url from the "Dashboard" to configure "c3e-file-sink": ```java -jar c3e-file-sink-prod-standalone.jar --username "File_Sink_Username" --url http://c3e.thegeez.net/file-sink/<YOUR PROJECT LINK> --root a/path/on/your/fs```
5. Run ```lein figwheel``` on your server where you are running "c3e-file-sink" (see here for more information about [Leiningen] and [Figwheel])
6. Edit your project in c3e with your fellow collaborators and see the project update live!
7. Invite fellow collaborators by giving them the url of your c3e project

[Leiningen]: https://leiningen.org/
[Figwheel]: https://github.com/bhauman/lein-figwheel


## About c3e
http://c3e.thegeez.net

Written by:
Gijs Stuurman / [@thegeez][twt] / [Blog][blog] / [GitHub][github]

[twt]: http://twitter.com/thegeez
[blog]: http://thegeez.net
[github]: https://github.com/thegeez
