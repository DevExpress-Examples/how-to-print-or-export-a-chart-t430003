<!-- default file list -->
*Files to look at*:

* **[MainPage.aspx](./CS/PrintAndExport/MainPage.aspx) (VB: [MainPage.aspx](./VB/PrintAndExport/MainPage.aspx))**
<!-- default file list end -->
# How to print or export a chart


<p>This example demonstrates print and export capabilities of the chart control. Besides, it shows how to configure chart print options.</p>


<h3>Description</h3>

<p>To print a chart, call the chart's&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientWebChartControl_Printtopic">Print</a>&nbsp;method, and to export it, call the&nbsp;<a href="https://documentation.devexpress.com/AspNet/DevExpressXtraChartsWebScriptsASPxClientWebChartControl_SaveToDisktopic.aspx">SaveToDisk</a>&nbsp;method. The following export formats can be used.<br>- pdf<br>-&nbsp;xls<br>- xlsx<br>-&nbsp;rtf<br>- mht<br>- png<br>- jpeg<br>- bmp<br>- tiff<br>- gif<br><br>If chart is printed or exported to a file format supported division to pages (pdf, rtf), then you can configure print/export parameters using an object accessed using the&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientWebChartControl_GetPrintOptionstopic">GetPrintOptions</a>&nbsp;method. This object allows you to specify the following options.<br>- Chart size mode using the&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetSizeModetopic">SetSizeMode</a>&nbsp;method;<br>- The portrait or landscape page orientation using the&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetLandscapetopic">SetLandscape</a>&nbsp;method;<br>- Page margins using the&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetMarginToptopic">SetMarginTop</a>,&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetMarginLefttopic">SetMarginLeft</a>,&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetMarginBottomtopic">SetMarginBottom</a>,&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetMarginRighttopic">SetMarginRight</a>&nbsp;methods;<br>-&nbsp;A paper kind using the&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetPaperKindtopic">SetPaperKind</a>&nbsp;method;<br>- If custom the paper kind is used, the paper's name, width and height using the&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetCustomPaperNametopic">SetCustomPaperName</a>,&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetCustomPaperWidthtopic">SetCustomPaperWidth</a>&nbsp;and&nbsp;<a href="https://documentation.devexpress.com/#AspNet/DevExpressXtraChartsWebScriptsASPxClientChartPrintOptions_SetCustomPaperHeighttopic">SetCustomPaperHeight</a>&nbsp;methods.</p>

<br/>


