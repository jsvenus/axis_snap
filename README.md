axis_snap
=========

Surveillance cameras are simple, relatively speaking.  Video management systems (VMSs) are not. VMS software is usually smothered with complex/costly feature licenses and its configuration appears incredibly quirky to the uninitiated.

This application was born from the need for camera snapshot exports every minute.  A simple task when coding against a camera.  When attempting to use the VMS this task could be potentially frustrating, limited, and slow.

While running, `axis_snap` will create zip archives of camera snapshots.  This is a great low-complexity, low-cost solution for long-term storage requirements.

## Compatibility
As a Windows service, it is only compatible with Microsoft Windows.  It's written in C# with .NET 2.0 -- it's safe to assume compatibility with any patched server running at least Windows 2003.

axis_snap only supports AXIS encoders at this time.
