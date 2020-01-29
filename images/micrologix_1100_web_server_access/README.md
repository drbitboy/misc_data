
# How to make Microsoft Internet Explorer 11 sort of work with an Allen-Bradley MicroLogix 1100 PLC Web Server

## 1) Put IP address of PLC into [Local Intranet] Zone
![](https://github.com/drbitboy/misc_data/raw/master/images/micrologix_1100_web_server_access/local_intranet_site.png)
## 2) Allow [Local Intranet] Zone to use Tabular Data Control (TDC)
![](https://github.com/drbitboy/misc_data/raw/master/images/micrologix_1100_web_server_access/local_intranet_allow_tdc.png)
## 2.1) All ActiveX settings in that dialog, up to the TDC-specific radio buttons are enabled, except for the following
    [High Safety] Permissions for components with manifests
    [Disable] Allow ActiveX Filtering
    ]Disable] Automatic prompting for ActiveX controls
    [Prompt] Download signed ActiveX controls
    [Disable] Download unsigned ActiveX controls
    [Disable] Run antimalware software on ActiveX controls
    [Prompt] Access data sources across domains
    [Disable] Allow dragging of content between domains into separate windows
    [Disable] Allow dragging of content between domains into the same window
    [Enable] Allow the TDC Control
