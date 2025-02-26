Modified version of SP Flash Tool for Motorola G24 / G24 Power (fogorow). 

This tool in particular was made by Tinno, and requires login to use at full potential.

## Usage

The tool can only be used to initialize a download:

```shell
$ flash_tool.exe -Scatter <scatter-file> -d DA_SWSEC_P325A_dl_forbidden3.bin -Option download
```



## Release notes (from the tool) 
##### TN_MTK_TSDC_FlashTool_V5.2316.10.exe Version update content

Adjustment note:
	Brush with a new DA named DA_SWSEC_2316_p325a_dl_forbidden2.bin（Remove the misc partition）
	The tool is downloaded in Download only mode, and returns to the format misc data end after downloading, in order to solve 	the problem of starting from the same partition after AB upgrade

##### TN_MTK_TSDC_FlashTool_V5.2316.11.exe Version update content

Adjustment note:
	Brush with a new DA named DA_SWSEC_2316_p325a_dl_forbidden3.bin（Remove the misc and seccfg partition）
	The tool is downloaded in Download only mode, and returns to the format misc data end after downloading, in order to solve 	the problem of starting from the same partition after AB upgrade# sp-flash-tool
