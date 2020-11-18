*Triggers - Integration with Python*
=============


Launch a Dollar Universe Task implemented as a Trigge.
http://github.com/Automic-Community/Triggers---Integration-with-Python

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Trigger_Python.zip
								
						


Documenation and Instructions
---

<div class="ipsType_textblock ipsPad_half description_content"><span><strong class="bbc">What does this do?</strong></span><br /> <br />
<p class="bbc_indent" style="margin-left: 40px;">this script will launch a Dollar Universe Task implemented as a Trigger (feature available in Dollar Universe 6.2 and up).</p>
<br />
<p class="bbc_indent" style="margin-left: 40px;"><strong class="bbc">usage example:</strong></p>
<br />
<p class="bbc_indent" style="margin-left: 40px;"><em class="bbc">Trigger.py -host bsalinux06 -port 6000 -login admin -pwd xxxxxxx -evttypename MYEVENT</em></p>
<br />
<p class="bbc_indent" style="margin-left: 40px;"><strong class="bbc">output:</strong></p>
<br />
<p class="bbc_indent" style="margin-left: 40px;"><em class="bbc">Authentication OK, Token is: 3fe46cf4-aa13-11e3-90c8-c095c3a56528</em></p>
<p class="bbc_indent" style="margin-left: 40px;"><em class="bbc">Status is: [success] For Trigger: [MYTRIGGER]</em></p>
<p class="bbc_indent" style="margin-left: 40px;"><em class="bbc">Launch Number is: 0000159</em></p>
<p class="bbc_indent" style="margin-left: 40px;"><em class="bbc">Authentication Token Deleted</em></p>
<br /><strong class="bbc"><span>What does this contain?</span></strong><br /><br /><br /><br />
<p class="bbc_indent" style="margin-left: 40px;">It contains two python scripts:</p>
<br />
<p class="bbc_indent" style="margin-left: 40px;"><strong class="bbc">triggerlib.py</strong>: contains core functions</p>
<p class="bbc_indent" style="margin-left: 40px;"><strong class="bbc">Trigger.py</strong>: contains the logic of authentication, calling the trigger, deleting the authentication token etc..</p>
<br /><strong class="bbc"><span>What can we do with this?</span></strong>
<ul class="bbc">
<li>Test the trigger mechanism implemented in Dollar Universe 6.2 and up</li>
<li>Adapt it for other use</li>
<li>Rewrite the code in another language using the same logic to integrate with any application</li>
<li>etc.</li>
</ul>
</div>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
