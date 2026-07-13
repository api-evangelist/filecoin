---
title: "FileStore"
url: "/systems/filecoin_files/file/filestore/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
FileStore - Local Storage for Files State reliable Theory Audit n/a Edit this section section-systems.filecoin_files.file.filestore The FileStore is an abstraction used to refer to any underlying system or device that Filecoin will store its data to. It is based on Unix filesystem semantics, and includes the notion of Paths. This abstraction is here in order to make sure Filecoin implementations make it easy for end-users to replace the underlying storage system with whatever suits their needs.
