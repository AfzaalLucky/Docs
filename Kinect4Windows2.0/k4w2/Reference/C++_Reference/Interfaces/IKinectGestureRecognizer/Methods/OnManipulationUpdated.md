IKinectGestureRecognizerManipulationHandler::OnManipulationUpdated Method  
=========================================================================  

Called after one or more input points have been initiated and subsequent motion (translation or zoom) is under way. <span id="syntaxSection"></span>

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
HRESULT OnManipulationUpdated(  
         IKinectManipulationUpdatedEventArgs *args  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*args*    
Type: IKinectManipulationUpdatedEventArgs  
The event data.  

<span id="ID4EP"></span>
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
TOCTitle : OnManipulationUpdated Method
RLTitle : IKinectGestureRecognizerManipulationHandler::OnManipulationUpdated Method
KeywordK : OnManipulationUpdated method
KeywordK : IKinectGestureRecognizerManipulationHandler::OnManipulationUpdated method
KeywordF : IKinectGestureRecognizerManipulationHandler::OnManipulationUpdated
KeywordF : OnManipulationUpdated
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationUpdated(IKinectManipulationUpdatedEventArgs)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationUpdated(IKinectManipulationUpdatedEventArgs)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationUpdated(IKinectManipulationUpdatedEventArgs)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler::OnManipulationUpdated
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
