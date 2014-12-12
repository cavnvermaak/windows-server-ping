windows-server-ping
===================

name: Ping 
  hosts: windows 

  tasks:
  - name: ping
    win_ping:

