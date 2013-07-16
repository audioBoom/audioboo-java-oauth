audioboo-java-oauth
===================

An example command line tool using OAuth to talk to audioboo.fm

Depends on [Signpost 1.2](https://code.google.com/p/oauth-signpost/) and the Commons Codec

You can compile & run using: 

```
javac -cp 'lib/*.jar' src/BooOAuth.java
java -cp 'lib/*.jar:.' BooOAuth
```

The project also includes BooOAuthUpload, which is a simple demonstration of uploading a boo:
```
javac -cp 'lib/*.jar' src/BooOAuthUpload.java
java -cp 'lib/*.jar:.' BooOAuthUpload /path/to/an_audio_file
```
