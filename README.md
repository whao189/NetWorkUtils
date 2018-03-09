# NetWorkUtils
this module just for android,  when the app need listener net work changed. etc :wifi ,mobile.


step :

1 your context implements INetWorkModule

2 when your context( Activity , Service , or Application),register it and unregister it


3 but Android 6.0 sometimes, the broadcast can'r receiver system notify when network changed,
  so you can implements "isDynamicRegister".

