# Violet
Container project for playing around with some concepts.

## Goals
Read large files with tokio::fs
Hash the large files.
Send large files through a series of gRPC services.
Use tokio tonic for handling gRPC.

## Notes
The files filled with random data was created using this command
```
$ dd if=/dev/urandom of=randomfile.bin bs=1m count=1024
```

