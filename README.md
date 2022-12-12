# Volatility

Volatility is an open-source memory forensics toolkit written in Python. Volatility allows us to analyse memory dumps taken from Windows, Linux and Mac OS devices and is an extremely popular tool in memory forensics. For example, Volatility allows us to:

List all processes that were running on the device at the time of the capture
List active and closed network connections
Use Yara rules to search for indicators of malware
Retrieve hashed passwords, clipboard contents, and contents of the command prompt and more
<br>
<br>
<br>
Volatility can be ran with <i><b>python3 vol.py</b></i>
<br>
<br>Options
<br>
-h = volatility help menu <br>
example <i>python3 vol.py -h</i>
-f = This argument is where you provide the name and location of the memory dump that you wish to analyse. <br>
example <i>python3 vol.py -f /path/to/my/memorydump.vmem</i> <br>
-v = This argument increases the verbosity of Volatility. This is sometimes useful to understand what Volatility is doing in cases of debugging. <br>
example <i>python3 vol.py -v</i>  <br>
-p = This argument allows you to override the default location of where plugins are stored. <br>
example <i>python3 vol.py -p /path/to/my/custom/plugins</i> <br>
-o = This argument allows you to specify where extracted processes or DLLs are stored. <br>
example <i>python3 vol.py -o /output/extracted/files/here</i> <br>
