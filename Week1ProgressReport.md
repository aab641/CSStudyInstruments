Hi everyone,

This week I was taught how to use Preston Moore's rrapper project. This tool allows us to test how a targeted application responds to anomalies within the operating system environment. There were some issues setting the tool up but we are operational!

* Worked with Preston to create and distribute a configured Ubuntu 32-bit VMWare image containing the installed project: https://drive.google.com/open?id=1LaSNHytG1jAg9Pa6vcuXgwWa7F5rzuss

* Found a system call ('fadvise64_64') in the "bin/cat" binary that rrwraper had not yet identified. Opened an issue: https://github.com/pkmoore/rrapper/issues/36
