<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/MasterDetailReportLoadedFromRepx/Form1.cs) (VB: [Form1.vb](./VB/MasterDetailReportLoadedFromRepx/Form1.vb))
* [XtraReport1.cs](./CS/MasterDetailReportLoadedFromRepx/SourceReports/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/MasterDetailReportLoadedFromRepx/SourceReports/XtraReport1.vb))
* [XtraReport2.cs](./CS/MasterDetailReportLoadedFromRepx/SourceReports/XtraReport2.cs) (VB: [XtraReport2.vb](./VB/MasterDetailReportLoadedFromRepx/SourceReports/XtraReport2.vb))
<!-- default file list end -->
# How to create a Master-Detail report type using two report layouts at runtime


<p>This example demonstrates how to create Master-Detail report, based on two report layouts (REPX files).<br />
The XtraReport.FindControl method is used to obtain the XRSubreport control instance. The subreport's FilterString property is adjusted via the XRSubreport.BeforePrint event handler.</p>

<br/>


