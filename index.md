<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
<!--  If necessary, please modify the charset parameter to specify the        -->
<!--  character set of your HTML page.                                        -->
<!--  ----------------------------------------------------------------------  -->

<META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">
<html>
<script src="https://www.google.com/recaptcha/api.js"></script>
<script>
 function timestamp() { var response = document.getElementById("g-recaptcha-response"); if (response == null || response.value.trim() == "") {var elems = JSON.parse(document.getElementsByName("captcha_settings")[0].value);elems["ts"] = JSON.stringify(new Date().getTime());document.getElementsByName("captcha_settings")[0].value = JSON.stringify(elems); } } setInterval(timestamp, 500); 
</script>

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <FORM> element to your page.             -->
<!--  ----------------------------------------------------------------------  -->

<form action="https://test.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8&orgId=00DcT000002CySP" method="POST">

<input type=hidden name='captcha_settings' value='{"keyname":"AvantiW2LreCAPTCHA","fallback":"true","orgId":"00DcT000002CySP","ts":""}'>
<input type=hidden name="oid" value="00DcT000002CySP">
<input type=hidden name="retURL" value="https://www.avanticorporate.com/">
<input type=hidden name="lead_source" id="lead_source" value="Website">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail"                                  -->
<!--  value="sfadmin+avanti@veltig.com">                                      -->
<!--  ----------------------------------------------------------------------  -->

<label for="first_name">First Name</label><input  id="first_name" maxlength="40" name="first_name" size="20" type="text" Required /><br>

<label for="last_name">Last Name</label><input  id="last_name" maxlength="80" name="last_name" size="20" type="text" Required /><br>

What can we help you with?:<select  id="00NcT000001Yj0X" name="00NcT000001Yj0X" title="What can we help you with?" required="required"><option value="">--None--</option><option value="Sales Inquiry">Sales Inquiry</option>
<option value="Equipment">Equipment</option>
<option value="National Accounts">National Accounts</option>
<option value="Design">Design</option>
<option value="Construction">Construction</option>
<option value="K-12 Schools">K-12 Schools</option>
<option value="Installation">Installation</option>
<option value="Resupply">Resupply</option>
<option value="Press/Media">Press/Media</option>
</select><br>

<label for="email">Email</label><input  id="email" maxlength="80" name="email" size="20" type="text" Required /><br>

<label for="description">Message</label><textarea name="description" Required></textarea><br>

<label for="phone">Phone</label><input  id="phone" maxlength="40" name="phone" size="20" type="text" /><br>

How did you hear about us?:<select  id="00NcT000001Yj29" name="00NcT000001Yj29" title="How did you hear about us?"><option value="">--None--</option><option value="Referral">Referral</option>
<option value="Google">Google</option>
<option value="LinkedIn">LinkedIn</option>
<option value="Instagram">Instagram</option>
<option value="Email">Email</option>
</select><br>

<div class="g-recaptcha" data-sitekey="6LfdLEotAAAAADt10zGVfCSzZSSVl3jX-vcVLmhz"></div><br>
<input type="submit" name="submit">

</form>
</html>
