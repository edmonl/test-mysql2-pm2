```
--- PM2 report ----------------------------------------------------------------
Date                 : Thu Aug 04 2022 16:19:11 GMT-0400 (Eastern Daylight Saving Time)
===============================================================================
--- Daemon --------------------------------------------------------------------
pm2d version         : 5.2.0
node version         : 16.16.0
node path            : /home/myuser/.npm-global/bin/pm2
argv                 : /home/myuser/stow/node-v16.16.0-linux-x64/bin/node,/home/myuser/.npm-global/lib/node_modules/pm2/lib/Daemon.js
argv0                : node
user                 : myuser
uid                  : 1000
gid                  : 1000
uptime               : 5min
===============================================================================
--- CLI -----------------------------------------------------------------------
local pm2            : 5.2.0
node version         : 16.16.0
node path            : /home/myuser/.npm-global/bin/pm2
argv                 : /home/myuser/stow/node-v16.16.0-linux-x64/bin/node,/home/myuser/.npm-global/bin/pm2,report
argv0                : node
user                 : myuser
uid                  : 1000
gid                  : 1000
===============================================================================
--- System info ---------------------------------------------------------------
arch                 : x64
platform             : linux
type                 : Linux
cpus                 : Intel(R) Xeon(R) CPU           X5670  @ 2.93GHz
cpus nb              : 6
freemem              : 10982146048
totalmem             : 16761569280
home                 : /home/myuser
===============================================================================
--- PM2 list ------------------------------------------------------------------
┌─────┬──────────┬─────────────┬─────────┬─────────┬──────────┬────────┬──────┬───────────┬──────────┬──────────┬──────────┬──────────┐
│ id  │ name     │ namespace   │ version │ mode    │ pid      │ uptime │ ↺    │ status    │ cpu      │ mem      │ user     │ watching │
├─────┼──────────┼─────────────┼─────────┼─────────┼──────────┼────────┼──────┼───────────┼──────────┼──────────┼──────────┼──────────┤
│ 0   │ index    │ default     │ 1.0.0   │ fork    │ 55478    │ 20s    │ 0    │ online    │ 0%       │ 46.9mb   │ myuser   │ disabled │
└─────┴──────────┴─────────────┴─────────┴─────────┴──────────┴────────┴──────┴───────────┴──────────┴──────────┴──────────┴──────────┘
===============================================================================
--- Daemon logs ---------------------------------------------------------------
/home/myuser/.pm2/pm2.log last 20 lines:
PM2        | 2022-08-04T16:14:05: PM2 log: PM2 version          : 5.2.0
PM2        | 2022-08-04T16:14:05: PM2 log: Node.js version      : 16.16.0
PM2        | 2022-08-04T16:14:05: PM2 log: Current arch         : x64
PM2        | 2022-08-04T16:14:05: PM2 log: PM2 home             : /home/myuser/.pm2
PM2        | 2022-08-04T16:14:05: PM2 log: PM2 PID file         : /home/myuser/.pm2/pm2.pid
PM2        | 2022-08-04T16:14:05: PM2 log: RPC socket file      : /home/myuser/.pm2/rpc.sock
PM2        | 2022-08-04T16:14:05: PM2 log: BUS socket file      : /home/myuser/.pm2/pub.sock
PM2        | 2022-08-04T16:14:05: PM2 log: Application log path : /home/myuser/.pm2/logs
PM2        | 2022-08-04T16:14:05: PM2 log: Worker Interval      : 30000
PM2        | 2022-08-04T16:14:05: PM2 log: Process dump file    : /home/myuser/.pm2/dump.pm2
PM2        | 2022-08-04T16:14:05: PM2 log: Concurrent actions   : 2
PM2        | 2022-08-04T16:14:05: PM2 log: SIGTERM timeout      : 1600
PM2        | 2022-08-04T16:14:05: PM2 log: ===============================================================================
PM2        | 2022-08-04T16:14:05: PM2 log: App [index:0] starting in -fork mode-
PM2        | 2022-08-04T16:14:05: PM2 log: App [index:0] online
PM2        | 2022-08-04T16:14:44: PM2 log: Stopping app:index id:0
PM2        | 2022-08-04T16:14:44: PM2 log: App [index:0] exited with code [0] via signal [SIGINT]
PM2        | 2022-08-04T16:14:44: PM2 log: pid=55096 msg=process killed
PM2        | 2022-08-04T16:18:51: PM2 log: App [index:0] starting in -fork mode-
PM2        | 2022-08-04T16:18:51: PM2 log: App [index:0] online

```


Please copy/paste the above report in your issue on https://github.com/Unitech/pm2/issues
