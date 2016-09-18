# A simple tool for directory structure scaffolding. 

## How to use

```
npm install moge -g
```

Create a simple m.dir file. An example can be found [here](https://github.com/4y0/moge/tree/master/examples/m.dir)
To scaffold the directory, run the moge command.

```
moge
```

## Moge syntax
```
directoryname fileename1,filename2,filename3,...filenameN
	subdirecotryname subdirectoryfilename1,subdirectoryfilename2....
		subsubdirectory subsubdirectoryfilename1,subsubdirectoryfilename2...
anotherdirectoryname anotherdirectoryfilename1,anotherdirectoryfilename2...
```

N.B: To create a file directly on the root directory, prepend the file name with a single space (no tabs)

```
 rootdirectoryfilename.js,rootdirectoryfilename2.css...
directoryname filename1,filename2...filenameN
```