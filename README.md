# IMPA migration on Windows using imapsync_2.264

Extract imapsync_2.264.zip

Edit file.txt and add your accounts to migrate

Use exemple: 

#From UOLHost to Other

imap.uhserver.com;hello@dominio.com.br;AccountPassordServerFrom;imap.serverdestination.com.br;hello@dominio.com.br;AccountPassordServerTo;--addheader --automap;
imap.uhserver.com;hello1@dominio.com.br;AccountPassordServerFrom;imap.serverdestination.com.br;hello1@dominio.com.br;AccountPassordServerTo;--addheader --automap;

Save file

on cmd.exe go to dir where is sync_loop_windows.bat 

on cmd.exe type

.\sync_loop_windows.bat 



