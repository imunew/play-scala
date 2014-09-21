play-scala
==========

### vagrant up

```
mac $ vagrant up
```

### activator new

```
mac $ vagrant ssh
vagrant $ cd /apps
vagrant $ sudo activator new
```

```
...

Browse the list of templates: http://typesafe.com/activator/templates
Choose from these featured templates or enter a template name:
  1) minimal-java
  2) minimal-scala
  3) play-java
  4) play-scala
(hit tab to see a list of all templates)
> 4
Enter a name for your application (just press enter for 'play-scala')
> {application name}
OK, application "{application name}" is being created using the "play-scala" template.

To run "{application name}" from the command line, "cd {application name}" then:
/apps/{application name}/activator run

To run the test for "{application name}" from the command line, "cd {application name}" then:
/apps/{application name}/activator test

To run the Activator UI for "{application name}" from the command line, "{application name}" then:
/apps/{application name}/activator ui
```

### activator run

```
vagrant $ cd {application name}
vagrant $ ./activator run
```

```
--- (Running the application from SBT, auto-reloading is enabled) ---

[info] play - Listening for HTTP on /0:0:0:0:0:0:0:0:9000

(Server started, use Ctrl+D to stop and go back to the console...)
```

### access from browser

[http://192.168.101.11:9000/](http://192.168.101.11:9000/)

```
[info] Compiling 5 Scala sources and 1 Java source to /apps/{application name}/target/scala-2.11/classes...
[info] 'compiler-interface' not yet compiled for Scala 2.11.1. Compiling...
[info]   Compilation completed in 43.508 s

...

[info] play - Application started (Dev)
```

