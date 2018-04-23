# PivotGrid - How to restore the layout when submitting a form using XmlXtraSerializer


<p>The PivotGrid extension does not have the built-in capability to restore a form state when submitting the form or refreshing a page. This example illustrates how to do this manually.</p><p>To accomplish this task, execute the following steps:</p><p>- Assign a delegate to the PreRender property;<br />
- Deserialize data from an XML file, which contains saved PivotGrid data. It is necessary to make sure that the structure of a file meets the PivotGrid data or add a check-up to the empty file;<br />
- Assign a delegate to the <a href="http://documentation.devexpress.com/#AspNet/DevExpressWebMvcPivotGridSettings_AfterPerformCallbacktopic"><u>AfterPerformCallback</u></a> property;<br />
- Serialize the PivotGrid data to the XML file.</p><p><strong>See also:</strong><strong><br />
</strong><a href="https://www.devexpress.com/Support/Center/p/E4219">PivotGrid - How to save/load field values' collapsed states together with pivot grid's layout</a><br />
<a href="https://www.devexpress.com/Support/Center/p/E20015">Save/load field values' collapsed states together with pivot grid's layout</a></p>

<br/>


