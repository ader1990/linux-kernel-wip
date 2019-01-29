### KVP daemon exits with 1 incorrectly

There should be an exit 0 if the flag -h is used:
https://github.com/torvalds/linux/blob/master/tools/hv/hv_kvp_daemon.c#L1391

