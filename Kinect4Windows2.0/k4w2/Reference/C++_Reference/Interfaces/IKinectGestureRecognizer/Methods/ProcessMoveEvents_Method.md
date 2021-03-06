IKinectGestureRecognizer::ProcessMoveEvents Method  
==================================================  

Processes pointer input and raises the [IKinectGestureRecognizer](../../IKinectGestureRecognizer.md) events appropriate to a pointer move action for the gestures and manipulations specified by the object's gesture settings. <span id="syntaxSection"></span>

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
HRESULT ProcessMoveEvents(  
         IKinectPointerPoint *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*value*    
Type: IKinectPointerPoint  
[in] The input point.  

<span id="ID4ET"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessMoveEvents Method
RLTitle : IKinectGestureRecognizer::ProcessMoveEvents Method
KeywordK : ProcessMoveEvents method
KeywordK : IKinectGestureRecognizer::ProcessMoveEvents method
KeywordF : IKinectGestureRecognizer::ProcessMoveEvents
KeywordF : ProcessMoveEvents
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.ProcessMoveEvents(IKinectPointerPoint)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.ProcessMoveEvents(IKinectPointerPoint)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.ProcessMoveEvents(IKinectPointerPoint)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::ProcessMoveEvents
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
