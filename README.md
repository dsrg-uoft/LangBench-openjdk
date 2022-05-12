# LangBench OpenJDK 13 Instrumentation
Use appropriate branch to build different instrumentations. Build instructions are same as OpenJDK. See README for original OpenJDK README.

## Enabling permissions
```
sudo sh -c 'echo -1 >  /proc/sys/kernel/perf_event_paranoid'
sudo sh -c 'echo 2 > /sys/bus/event_source/devices/cpu/rdpmc'
```
