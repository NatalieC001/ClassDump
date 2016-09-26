# ClassDump
http://stevenygard.com/projects/class-dump/


This is a command-line utility for examining the Objective-C runtime information stored in Mach-O files. It generates declarations for the classes, categories and protocols. This is the same information provided by using ‘otool -ov’, but presented as normal Objective-C declarations, so it is much more compact and readable.

Why use class-dump?

It’s a great tool for the curious. You can look at the design of closed source applications, frameworks, and bundles. Watch the interfaces evolve between releases. Experiment with private frameworks, or see what private goodies are hiding in the AppKit. Learn about the plugin API lurking in Mail.app.
