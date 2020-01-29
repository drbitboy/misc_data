
# How to make Microsoft Internet Explorer 11 work (sort of) with an Allen-Bradley MicroLogix 1100 PLC Web Server

## 1) Put IP address of PLC into [Local Intranet] Zone
![](https://github.com/drbitboy/misc_data/raw/master/images/micrologix_1100_web_server_access/local_intranet_site.png)

## 2) Allow [Local Intranet] Zone to use Tabular Data Control (TDC); see item 2.1 below also.
![](https://github.com/drbitboy/misc_data/raw/master/images/micrologix_1100_web_server_access/local_intranet_allow_tdc.png)

## 2.1) All ActiveX settings in that dialog are [Enabled] up to and including the TDC-specific radio buttons, except for the following
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
