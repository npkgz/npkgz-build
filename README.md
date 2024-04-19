npkgz - simply pack your nodejs application into tgz archives
=======================================================




Hooks
----------------


## deploy ##

Description: triggered by command `update` after packaging has finished
File: `<project>/.hooks/deploy`

```bash
#!/usr/bin/env bash

hook_deploy(){
    # do something
}
```