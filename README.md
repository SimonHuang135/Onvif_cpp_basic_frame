# Onvif_cpp_basic_frame_lib produced by gSoap
Linux - Ubuntu 16.04
--------------------------------------------------------
Installation of goSoap
--------------------------------------------------------
https://blog.csdn.net/qq_28351465/article/details/73743660?utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~all~sobaiduend~default-2-73743660.nonecase&utm_term=gsoap%20linux%20%E5%AE%89%E8%A3%85&spm=1000.2123.3001.4430

--------------------------------------------------------
Installation of onvif
--------------------------------------------------------
https://blog.csdn.net/u010871058/article/details/71403962

--------------------------------------------------------
onvif plan:
--------------------------------------------------------
https://blog.csdn.net/u012084827/article/details/12202267

--------------------------------------------------------
cmd-produce-onvif.h:
--------------------------------------------------------
wsdl2h -o -s -t typemap.dat -o onvif.h  http://www.onvif.org/onvif/ver10/device/wsdl/devicemgmt.wsdl http://www.onvif.org/onvif/ver10/media/wsdl/media.wsdl http://www.onvif.org/onvif/ver10/event/wsdl/event.wsdl http://www.onvif.org/onvif/ver10/display.wsdl http://www.onvif.org/onvif/ver10/deviceio.wsdl http://www.onvif.org/onvif/ver20/imaging/wsdl/imaging.wsdl http://www.onvif.org/onvif/ver20/ptz/wsdl/ptz.wsdl http://www.onvif.org/onvif/ver10/receiver.wsdl http://www.onvif.org/onvif/ver10/recording.wsdl http://www.onvif.org/onvif/ver10/search.wsdl http://www.onvif.org/onvif/ver10/network/wsdl/remotediscovery.wsdl http://www.onvif.org/onvif/ver10/replay.wsdl http://www.onvif.org/onvif/ver20/analytics/wsdl/analytics.wsdl http://www.onvif.org/onvif/ver10/analyticsdevice.wsdl http://www.onvif.org/ver10/actionengine.wsdl http://www.onvif.org/ver10/pacs/accesscontrol.wsdl http://www.onvif.org/ver10/pacs/doorcontrol.wsdl

--------------------------------------------------------
cmd-produce-c/cpp:
--------------------------------------------------------
soapcpp2 -c  onvif.h -x -I ../gsoap-2.8/gsoap/import -I ../gsoap-2.8/gsoap
##############################################################################
soapcpp2 onvif.h -x -I ../gsoap-2.8/gsoap/import -I ../gsoap-2.8/gsoap

----------------------------------------------------------
Onvif development
--------------------------------------------------------
https://wenku.baidu.com/view/21128cfdba0d4a7303763a0d.html

--------------------------------------------------------
Demo
--------------------------------------------------------
1. 
https://download.csdn.net/download/jxjrj/7803425

2.
https://download.csdn.net/download/shcdwz1234/9761846


3.
http://blog.csdn.net/ghostyu/article/details/8182516
https://download.csdn.net/download/ghostyu/4766025

4.
http://blog.csdn.net/ghostyu/article/details/8208428
http://download.csdn.net/detail/ghostyu/4796093

5.
http://blog.csdn.net/ghostyu/article/details/8432760
