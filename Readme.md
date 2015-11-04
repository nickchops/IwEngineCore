IwEngineCore
============

A very lightweight 3D engine module built on top of Marmalade's
IwGx, IwGraphics and s3e I/O APIs. It adds world/actor concepts and
basic scene, camera and control management.

A tutorial based around this project is in the Marmalade official docs here:
http://docs.madewithmarmalade.com/x/uQXH

It is based on the existing project here: https://github.com/marmalade/gbsgamejam/tree/master/CPPGameTemplate

Eventually this should get integrated into the SDK.

IwEngineCore.mkf is not designed to be built directly as a library. It can be
included in an MKB project file using: subproject IwEngineCore
