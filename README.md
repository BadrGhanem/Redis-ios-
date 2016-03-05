# Redis-ios-
Redis support for ios


Works on simulator and device:

1) Download the file. 

2) Put the whole folder inside your project.

3) "Enable Bitcode" should be set to No

4) include this headers inside your uiviewcontroller:

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <signal.h>
#include "hiredis.h"
#include "async.h"
#include "libevent.h"

Now you are done. Enjoy!

For more information read on how to get started: https://github.com/redis/hiredis
