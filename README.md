# Zombiender
regla YARA  que se puede ajustar o modificar según las necesidades y características específicas del entorno de análisis.

Esta regla busca la presencia de las cadenas "Zombiender", "wuauser.exe", "spoolsv.exe", "wmiprvse.exe", "wbemtest.exe" y "winmgmt.exe" en el archivo analizado. Si todas las cadenas se encuentran presentes.
la regla considera que el archivo es probablemente Zombiender malware.
