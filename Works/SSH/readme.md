https://serverfault.com/questions/200249/how-to-tunnel-windows-remote-desktop-through-ssh-using-a-linux-box

Node:
0 - QubesOS
1 - pFsense, on Xen
2 - Windows

# Tunnel to pFsense
ssh -p 22 -L 4001:192.168.3.126:4000 me@192.168.3.137

# Windows Open NX ports
nx://windows.home:4000

# Connect on Remote's localhost
nx://localhost:4001
