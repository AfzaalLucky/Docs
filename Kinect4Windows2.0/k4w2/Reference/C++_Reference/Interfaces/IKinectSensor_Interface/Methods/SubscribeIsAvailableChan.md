IKinectSensor::SubscribeIsAvailableChanged Method  
=================================================  

Subscribes an event handler that is raised when the availability of the Kinect Sensor changes. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public:  
HRESULT SubscribeIsAvailableChanged(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] The handle to the event handler.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SubscribeIsAvailableChanged Method
RLTitle : IKinectSensor::SubscribeIsAvailableChanged Method
KeywordK : SubscribeIsAvailableChanged method
KeywordK : IKinectSensor::SubscribeIsAvailableChanged method
KeywordF : IKinectSensor::SubscribeIsAvailableChanged
KeywordF : SubscribeIsAvailableChanged
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.SubscribeIsAvailableChanged(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.SubscribeIsAvailableChanged(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.SubscribeIsAvailableChanged(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::SubscribeIsAvailableChanged
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
