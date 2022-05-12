# Lab 9 — YANG
## Assignment:
-   Install pyang and PlantUML
-   Given intrusiondetection.yang, run pyang to generate intrusiondetection.yin and intrusiondetection.uml
-   RUn PlantUML to generate intrusiondetection.png

## Work done on my Raspberry Pi:
```console
pi@ctmpi: ~/demo $ pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef
pi@ctmpi: ~/demo $  python3 -m plantuml intrusiondetection.uml
[{'filename': 'intrusiondetection.uml', 'gen_success': True}]
```
```console
pi@ctmpi: ~/demo $ gimp -h
Usage:
  gimp [OPTION…] [FILE|URI...]

GNU Image Manipulation Program

Help Options:
  -h, --help                          Show help options
  --help-all                          Show all help options
  --help-gegl                         Show GEGL Options
  --help-gtk                          Show GTK+ Options

Application Options:
  -v, --version                       Show version information and exit
  --license                           Show license information and exit
  --verbose                           Be more verbose
  -n, --new-instance                  Start a new GIMP instance
  -a, --as-new                        Open images as new
  -i, --no-interface                  Run without a user interface
  -d, --no-data                       Do not load brushes, gradients, patterns, ...
  -f, --no-fonts                      Do not load any fonts
  -s, --no-splash                     Do not show a splash screen
  --no-shm                            Do not use shared memory between GIMP and plug-ins
  --no-cpu-accel                      Do not use special CPU acceleration functions
  --session=<name>                    Use an alternate sessionrc file
  -g, --gimprc=<filename>             Use an alternate user gimprc file
  --system-gimprc=<filename>          Use an alternate system gimprc file
  -b, --batch=<command>               Batch command to run (can be used multiple times)
  --batch-interpreter=<proc>          The procedure to process batch commands with
  -c, --console-messages              Send messages to console instead of using a dialog
  --pdb-compat-mode=<mode>            PDB compatibility mode (off|on|warn)
  --stack-trace-mode=<mode>           Debug in case of a crash (never|query|always)
  --debug-handlers                    Enable non-fatal debugging signal handlers
  --g-fatal-warnings                  Make all warnings fatal
  --dump-gimprc                       Output a gimprc file with default settings
  --show-playground                   Show a preferences page with experimental features
  --display=DISPLAY                   X display to use

pi@ctmpi: ~/demo $ gimp -a intrusiondetection.png
![lab9](https://user-images.githubusercontent.com/25110110/167980478-609e795d-705c-4171-b8fd-3e8d50e3067c.png)
