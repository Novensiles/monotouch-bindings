
Couchbase.dll: libCouchCocoa.a libTouchDB.a bin/Debug/Couchbase.dll
	cp bin/Debug/Couchbase.dll .

bin/Debug/Couchbase.dll: Couchbase.csproj ApiDefinition.cs StructsAndEnums.cs libCouchCocoa.linkwith.cs	libTouchDB.linkwith.cs
	/Applications/Xamarin\ Studio.app/Contents/MacOS/mdtool build -p:Couchbase

clean:
	-rm -rf bin *dll

foo:
	git clone git://github.com/couchbaselabs/TouchDB-iOS.git
	(cd TouchDB-iOS; git submodule init; git submodule update)


